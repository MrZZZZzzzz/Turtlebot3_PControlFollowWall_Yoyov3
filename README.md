# Turtlebot3_PControlFollowWall_Yoyov3
This project is a final course project on intelligent robotics at Southern University of Science and Technology (SUSTech) in spring 2022.

This project implements two turtlebot3s walking along a wall inside a maze while recognizing and taking pictures of moving Pokémon attached to the wall. We set the p-controller so that Turtlebot3 can walk along the wall relatively smoothly and smoothly and detect the Pokémon in real time based on the trained Yolov3, and finally the task is completed well, but there may be lag due to running two networks at the same time.

## System Requirement
- Ubuntu18.04
- ROS Melodic

## Configuration
Assume that you know basic operations concerning workspace compilation and path configuration, etc. And the tutorial is here: http://wiki.ros.org/ROS/Tutorials
