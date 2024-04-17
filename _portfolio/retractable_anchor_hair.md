---
title: "Retractable Anchor Hairs"
author_profile: true
key: 1
date: 2023-04-26
excerpt: "Pneumatic Soft Robots, Origami Structure Design, Laser Cutting"
header:
  teaser: /assets/images/hair-teaser.gif
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

Since January 2023, I have been working as a research assistant in the Hawkes Lab at UCSB, contributing to a groundbreaking research under the direction of Ph.D. candidate Nicholas Naclerio. Our focus is on developing a fast, steerable burrowing soft robot using a tip-extension mechanism. The goal of this project is to enhance its anchoring capabilities by employing retractable hairs.

## Video Demo
<iframe width="560" height="315" src="https://www.youtube.com/embed/jS_yr_tqjiI?si=pfDcjTJoxjIPyB-N" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Design
Drawing inspiration from the complex root systems of plants, our tip-extending soft robot is designed to burrow into soil with lest effort while providing robust anchorage. Like how plant roots enhance their grip by expanding their surface area with branches and root hairs, we adopted a similar approach by engineering hair-like structures for our burrowing robots.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/hair-robot.png" alt="Burrowing Robot with Retractable Hairs" style="width: 100%;">

However, integrating hairs onto the robot is a nuanced work. Given the robot's key feature of tip-extension, these hairs needed to be both soft for retractability and sufficiently rigid for effective anchoring.

To meet this intricate demand, I crafted the hairs using Thermoplastic Polyurethane (TPU) material. By applying Kirigami techniques, I manipulated the TPU strip's width, creating variable flexural strengths at different segments. This method allows the strip to naturally fold into barb-shaped hairs when attached to the robot with Dyneema tape ensuring the hairs can retract or extend smoothly with the robot's movements.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/hair-design.png" alt="Hair Design" style="width: 100%;">

This design significantly increases the soft robot’s anchoring force and remains straightforward to manufacture. The TPU strips and Dyneema tape are processed with a laser cutter and could easily be assembled together. This facilitates rapid prototyping, greatly reduced iteration time.

## Next Step
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/hair-regolith.jpg" alt="Low-gravity Test Device" style="width: 100%;">

Our burrowing robot with retractable hairs has gone through the lunar regolith simulant field tests in NASA laboratory, and will be validated through a low-gravity test Blue Origin flight in the near future. We anticipate this technology will enhance the anchoring capabilities of rovers in low-gravity space exploration missions on the Moon, Mars, and astroids.



<!-- <iframe
    width="100%"
    height="50px"
    src="https://www.youtube.com/embed/aCotjAaHfwM"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe> -->

