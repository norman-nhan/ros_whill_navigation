# ros_whill_navigation
This repository is for learning autonomous driving 
## Initialization 
In this experiment, I have used the following things:
1. RPLIDAR A2M8
2. WHILL
## Packages installation
These are 4 main packages that I used in this experiment:
1. rplidar_ros from robopeak for lidar
2. ros_whill from WHILL for robot
3. slam_gmapping from ros-perception for creating static map
4. husky_navigation from husky for autonomious driving
```bash
git clone https://github.com/robopeak/rplidar_ros.git
git clone https://github.com/WHILL/ros_whill.git
git clone https://github.com/ros-perception/slam_gmapping.git
git clone https://github.com/husky/husky.git
```
## Implementation
After creating map, I execute these 3 launch_file in different terminals in order to perform the autonomous driving.
1. For WHILL
```bash
roslaunch ros_whill ros_whill.launch
```
2. For RPLIDAR
```bash
roslaunch rplidar_ros rplidar.launch
```
3. For Husky Navigation
```bash
roslaunch husky_navigation amcl_demo_nhan.launch
```
