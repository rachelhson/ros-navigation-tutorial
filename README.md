# ros-navigation-tutorial

Followed :  http://wiki.ros.org/navigation/Tutorials

### Navigation Stack

![image](https://user-images.githubusercontent.com/52179017/126206235-86abad20-fafc-4096-9efa-684d3199a6d5.png)





### Localization 
1. use AMCL using created map, and make sure that the robot stays localized
2. initialpose for the robot in rviz with reasonable accuracy is important 
3.`rostopic echo /amcl_pose` command will display any new /amcl_pose, which is the ROS topic represents the location of the robot on the map.

### dwa_local_planner :
http://wiki.ros.org/dwa_local_planner

