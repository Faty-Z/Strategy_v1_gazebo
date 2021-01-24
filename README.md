# Strategy_v1_gazebo

This program is used to model a 4-wheel mobile robot, using URDF (Unified Robot Description Format) and RViz to visualize it, as well as Gazebo to simulate it in real time.


Then there are 3 nodes written in python: 
-Recovery of Lidar data 
-Obstacle avoidance 
-Moving from one point to another

Please run the code in Ubuntu, using the following commands:

cd fatima-project
roscore cd simulation_ws 
catkin_make source devel/setup.bash 
roslaunch m4wr_description rviz.launch 
roslaunch m4wr_description spawn.launch 
rosrun gazebo_ros gazebo
