# Pepper ROS

Alternative all-in-one repository for all Pepper ROS related packages. In this repository Pepper robot also works in a Gazebo simulation.

In Aldebaran code Pepper was falling after running simulation and with ROS Kinetic Kame and Gazebo 7 we experiences weird `gravity bug`.

<p align="center">
  <img src="http://oi63.tinypic.com/5p3czr.jpg" alt="Robot Pepper in working simulator Gazebo" />
</p>

## Install
```sh
mkdir -p ~/pepper_ws/src
cd ~/pepper_ws/src
git clone git@github.com:michtesar/pepper_ros.git
cd ~/pepper_ws
catkin build
source devel/setup.bash
cd ~
```
