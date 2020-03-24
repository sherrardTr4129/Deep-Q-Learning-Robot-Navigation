# Deep-Q-Learning-Robot-Navigation
Robot Navigation Using A Deep Q-Learning Model 

## Prerequisites

Make sure you have already installed the [turtlebot2](https://github.com/ROBOTIS-GIT/turtlebot3.git), [turtlebot3\_msgs](https://github.com/ROBOTIS-GIT/turtlebot3_msgs.git), and [turtlebot3\_simulations](https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git) packages into your catkin build system.

## Gazebo Setup
1) Copy the KGCOE\_MODEL directory into the turtlebot3\_gazebo/models directory
2) Copy the turtlebot3\_KGCOE.world file into the turtlebot3\_gazebo/worlds directory.
3) Copy the turtlebot3\_KGCOE.launch file into the turtlebot3\_gazebo/launch directory.
4) rebuild catkin workspace
5) Execute 'roslaunch turtlebot3\_gazebo turtlebot3\_KGCOE.launch'
