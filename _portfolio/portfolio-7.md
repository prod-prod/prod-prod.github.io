---
title: "Generate the map of environment in ROS"
excerpt: "Generate the map of the environment by reading odometry, lidar and camera data<br/><img src='/images/projects/MapCreation.png'>"
collection: portfolio
---


### Paper

[RTAB-Map as an Open-Source Lidar and Visual SLAM Library for Large-Scale and Long-Term Online Operation](https://introlab.3it.usherbrooke.ca/mediawiki-introlab/images/7/7a/Labbe18JFR_preprint.pdf)

Important: the project does not implement the paper, but uses the paper to answer some questions. Paper is just as a reference for better understanding.


### About

In the project, we use RTAB-Map to build the 3-dimentional map of the robot environment.

To get more about RTAB-Map you can see the [official wiki page of the project](http://wiki.ros.org/rtabmap_ros).

RTAB-Map is only one of many algorithms. If you want to get familiar with other, check the following paper [Comparison of Various SLAM Systems for Mobile Robot in an Indoor Environment](https://www.researchgate.net/publication/328007381_Comparison_of_Various_SLAM_Systems_for_Mobile_Robot_in_an_Indoor_Environment).

Current project just provides an example how you can run RTAB-Map inside the Gazebo simulation.


### Implementation

For the implementation we will use `rtabmap_ros` ROS node.


### Envorinment

To implemet and verify we use [Gazebo](http://gazebosim.org/). It is a free tool for robot simulation.


### Code

All code is available on the [Github](https://github.com/kurbakov/generate-map-from-robot)
