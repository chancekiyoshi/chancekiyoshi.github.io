---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Pohnpei Taxi Number List"
date: 2026-07-19
published: true
labels:
  - HTML
  - Web Development
  - Claud AI
  - Community Project
  - Pohnpei
summary: "An interactive web application built with HTML and Claude AI that provides direct-dial access to Pohnpei's local taxi services, bridging the digital accessibility gap where public transportation info is not available online."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

In Pohnpei, Micronesia, local taxi services are the main form of public transportation since there are no public buses or ride share apps like Uber or Lyft. However, finding a taxi number can be a real hassle. Physical phone books are out of date, taxi numbers aren't listed on Google, and calling FSM Telecom for a directory lookup costs extra money. 

To solve this for my community, I created a simple, direct web directory that centralizes local taxi dispatch numbers in one place for free. The site features tap-to-call buttons so anyone browsing on a mobile phone can immediately dial a cab with a single click—no copying, pasting, or directory fees required.

To get the project up and running quickly, I used Claude AI to help generate and refine the underlying HTML code and layout, then customized the design for quick mobile navigation. The website is currently live, and I am now working on turning it into a downloadable mobile app to make accessing local taxi services even easier.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
