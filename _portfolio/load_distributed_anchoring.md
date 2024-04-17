---
title: "Robotic Anchoring with Intelligent Load Distribution"
author_profile: true
date: 2023-07-01
excerpt: "Real-time Control, Test Automation, Data Analysis"
header:
  teaser: /assets/images/anchoring_teaser.jpg
---

{% comment %} 
sidebar:
  - title: "Role"
    image: http://placehold.it/350x250
    image_alt: "logo"
    text: "Designer, Front-End Developer"
  - title: "Responsibilities"
    text: "Reuters try PR stupid commenters should isn't a business model"
{% endcomment %} 

Since January 2023, I have been working as a research assistant in the Hawkes Lab at UCSB, contributing to a groundbreaking research under the direction of Ph.D. candidate Nicholas Naclerio. Our focus is on developing a fast, steerable burrowing soft robot using a tip-extension mechanism. The goal of this project is to enhance its anchoring capabilities through a multi-anchor load distribution approach.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/anchoring.jpg" alt="Experiment Setup" style="width: 100%;">

## Design
A significant part of my contribution to this project involved developing a load-distributed anchoring system. This system allows for the individual loading of anchors while monitoring their force profiles. By doing so, it preloads the anchors to their maximum force capacity, thereby preventing the chain reaction typically caused by the failure of a single anchor.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/anchoring-force.png" alt="Predicted Maximum Force" style="width: 100%;">

Although the concept is straightforward, implementing it effectively is challenging. The preloading process must be precisely controlled to stop just shy of reaching maximum force capacity. Any deviation — either too much or too little — could result in anchor failure.

Starting from scratch, I engineered the experimental setup and gathered crucial data through hundreds of tests. Utilizing force sensors and data analysis techniques including machine learning process, I developed a system capable of predicting the maximum uprooting force based on preceding force curves in real-time. This system then controls the preloading process accordingly. Our load distribution method successfully increases the total anchoring force to 97% of its theoretical maximum, compared to the 75% achieved without preloading. 

This endeavor required a diverse skillset: I gained experience in force sensor setup, calibration, and ADC manipulation; conducted data analysis, utilizing data smoothing filters, machine learning algorithms, and MATLAB; programmed Arduino for test system control and signal processing; constructed the test system via soldering boards, crimping, and assembling cables; and built test equipment using tools such as 3D printers, laser cutters, power tools, and McMaster components.

## Poster Presentation
On September 14, 2023, I had the opportunity to present our work at the [Southern California Robotics Symposium 2023](https://sites.uci.edu/scr2023/) during the poster presentation session.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/anchoring-SCR.jpg" alt="SCR Poster Presentation" style="width: 100%;">
[View Poster]({{ site.url }}{{ site.baseurl }}/assets/images/anchoring-poster.png)

## Paper
For a more detailed overview of my contributions to this project, please refer to the [published abstract]({{ site.url }}{{ site.baseurl }}/assets/Advancing Robotic Anchoring with Intelligent Load Distribution (SCR 2023 Abstract).pdf).

<!-- ## Video Demo
<iframe
    width="100%"
    height="50px"
    src="https://www.youtube.com/embed/T6qRhCT54ms"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe> -->