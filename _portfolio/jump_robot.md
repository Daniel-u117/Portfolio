---
title: "Rolling-Jumping Robot"
author_profile: true
date: 2022-06-14
excerpt: "Robotics Design, Motor Control, Programming (Arduino)"
header:
  teaser: /assets/images/jumping-robot.jpg
---

In my junior year of college, I joined the ME 153 - Introduction to Mechanical Engineering Design course as a Physics student. As a team with Yelin Mao, we completed a robotics project in this quater-long course.

## A Robotic Scout
Over the past decade, robotics has increasingly played a pivotal role in rescue operations following disasters. Robots can venture into hazardous environments, searching for survivors, making the rescue mission more effective. Our project focuses on addressing the challenge of locating survivors within collapsed buildings post-earthquake, a scenario where obstructions such as stairs, furniture, and construction debris can impede traditional wheeled robots.

## Engineering Design
Taking inspiration from nature, specifically creatures like locusts and frogs known for their jumping capabilities, our project explores a robotic design that incorporates a hopping mechanism. This approach enables the robot to navigate and overcome obstacles that would be insurmountable for conventional wheeled, tracked, or legged robots. We've developed a prototype of a rescue robot designed to operate in collapsed structures, maneuvering over complex terrain by leaping over obstructions. The design maintains a cylindrical shape with two wheels for movement, optimizing its size and minimizing the risk of damaging any structural supports upon landing.

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/jumping-robot.jpg" alt="Robot Photo" style="width: 100%;">

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/jumping-model.jpg" alt="Robot Design" style="width: 100%;">

Our prototype features a two-wheeled design powered by an Arduino Uno Rev3 microcontroller. The robot consists of two primary components: the movement mechanism and the jumping module.
- **Movement Mechanism**: This part uses a TB6612 motor driver connected to the microcontroller, controlling two DC motors that drive the wheels. Stability and balance are managed through data from an MPU-6050 sensor, which informs a PID balance algorithm.
- **Jumping Module**: A servo motor actuates a rack and half-pinion mechanism, compressing two coil springs to store energy. Upon release, the rack strikes the ground, propelling the robot into a hop. The servo motor, with a torque of 35 kg-cm (3.5 Nm), generates a force of 318 N through the pinion taht compresses the two springs. A latching mechanism them release the rack and launches the robot up to 70 cm high.  

## Poster Presentation
On Jume 7, 2022, we had the opportunity to present our work at the ME 153 Poster Competition Design Fair. 

<img src="{{ site.url }}{{ site.baseurl }}/assets/images/jumping-poster.png" alt="Jumping Robot Poster" style="width: 100%;">

[View Poster]({{ site.url }}{{ site.baseurl }}/assets/images/jumping-poster.png)

## Paper
For a more detailed overview of this project, please check out the [abstract]({{ site.url }}{{ site.baseurl }}/assets/A Two-Wheel Self-Balance Robot Capable of Jumping.pdf) I drafted.