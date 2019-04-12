# RPG_sim_OD description
This is  a package for ROS PX4 GAZEBO simulation for drone control based on object detection using tensorflow.  
# Prerequisite
1/Install RPG follow this instruction:  
https://dev.px4.io/en/setup/dev_env_linux.html#gazebo-with-ros  
2/ Follow this instruction to understand how to create a package in ros  
https://darienmt.com/autonomous-flight/2018/11/25/px4-sitl-ros-example.html  
3/ Read this tutorial to understand offboard mode in mavros  
https://dev.px4.io/en/ros/mavros_offboard.html  
# Using
1/Clone this respository.    
2/Copy launch files to your root folder.  
3/Change links in launch files to fit your need.  
4/From your root folder, "catkin_make".
5/After successfully make the package,open a new cmd window:  
cd to your root folder
./launch-tqk_od  
6/Open a new cmd window:  
~/<your root folder>/devel/setup.bash 
rosrun tqk_od offb_node.py  
  
