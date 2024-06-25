# Turtlebot Autonomous Navigation in ROS Gazebo using Reinforcement Learning

## System Requirements

| Requirement              | Version / Release            |
|--------------------------|------------------------------|
| **Operating System**     | Ubuntu 16.04  |
| **ROS Distribution Release** | *ROS2*               |
| **Pythin Version**          | python 3.9               |


## Overview

The project involves the development and evaluation of two robot navigation models using reinforcement
learning (RL). The goal is to navigate a robot in an unknown environment using ROS for
real-time interaction. This includes path finding and obstacle avoidance. Two models are explored: the first utilizes an action value-function with
linear function approximation, and the second employs a policy gradient method with non-linear
function approximation. Each model is tuned and assessed based on its ability to effect
## Setup & Configuration

### Setting up this repository with a new catkin workspace

Create a new catkin workspace.

In your terminal shell, navigate to your intended directory for your new workspace and execute the following commands, replacing `<wsname>` with your intended workspace name.

```bash
$ mkdir -p <wsname>/src
$ cd <wsname>/src/
$ catkin_init_workspace
$ cd ..
$ catkin_make



