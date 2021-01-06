---
title: "Robot localization in ROS"
excerpt: "Detect the location of the robot with particle filter and ROS<br/><img src='/images/projects/RobotLocalization.png'>"
collection: portfolio
---

### Paper

[Monte Carlo Localization for Mobile Robots](https://www.ri.cmu.edu/pub_files/pub1/dellaert_frank_1999_2/dellaert_frank_1999_2.pdf)


### About

In the project, we use Monte Carlo localization method, to detect the exact position of the robot in the 2 dimentional space.
Map is known, and we have access to robot odometrzy and sensor data.

About Monte Carlo localization from [Wikipedia](https://en.wikipedia.org/wiki/Monte_Carlo_localization):

> Monte Carlo localization (MCL), also known as particle filter localization, is an  algorithm for robots to localize using a particle filter. Given a map of the environment, the algorithm estimates the position and orientation of a robot as it moves and senses the environment.


### Implementation

For the implementation we will use `amcl` ROS node, available as part of the navigation ROS stock. 

If you want to know more about the ROS node, visit the [official ROS node page](http://wiki.ros.org/amcl).


### Envorinment

To implemet and verify we use [Gazebo](http://gazebosim.org/). It is a free tool for robot simulation.


### Code

All code is available on the [Github](https://github.com/kurbakov/robot-localization)
