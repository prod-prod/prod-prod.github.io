---
title: "Robot localization in ROS"
excerpt: "Detect the location of the robot with particle filter and ROS<br/><img src='/images/projects/RobotLocalization.png'>"
collection: portfolio
---


### About algorithm

From [Wikipedia](https://en.wikipedia.org/wiki/Monte_Carlo_localization):

> Monte Carlo localization (MCL), also known as particle filter localization, is an  algorithm for robots to localize using a particle filter. Given a map of the environment, the algorithm estimates the position and orientation of a robot as it moves and senses the environment.


### Algorithm implementation

For the implementation we will use `amcl` ROS node, available as part of the navigation ROS stock. 

If you want to know more about the ROS node, visit the [link](http://wiki.ros.org/amcl).


### Envorinment

To implemet and verify we use [Gazebo](http://gazebosim.org/). It is a free tool for robot simulation.


### Code

All code is available on he [Github](https://github.com/kurbakov/robot-localization)
