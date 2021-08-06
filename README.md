# warehous_simulation


A simulation of basic robot localization (SLAM) and navigation in warehouse environment

**Author:** [Wang Han](http://wanghan.pro), Nanyang Technological University, Singapore


## Table of Contents:
- install ROS Package
- Clone repository
- Launch ROS
- Robot Control
- Simulation



## **install ROS Package**
```
sudo apt-get install ros-melodic-hector-trajectory-server ros-melodic-slam-gmapping ros-melodic-navigation
```


##  Clone repository
```
    cd ~/catkin_ws/src
    git clone https://github.com/wh200720041/warehouse_navigation.git
    cd ..
    catkin_make
    source ~/catkin_ws/devel/setup.bash
```

## Launch ROS
```
    roslaunch warehouse_simulation warehouse_simulation.launch
```
Note that it takes a few minutes to load model upon first launch

## Robot Control
You can use keyboard (arrow keys) to manually control the robot (select cmd window first)


## Simulation 
 A robot is simulated at the center of the environment, with 2D  slam and robot navigation algorithm. 


![image](https://user-images.githubusercontent.com/86157318/124262727-0cd87d80-db3b-11eb-9bb5-2d8270397337.png)
