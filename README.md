
web_server
=====================================================================

This package contains the visulation of robot model and robot model controller in web server.

Dependencies
=====================================================================
[The MoveIt! package](https://github.com/fontyssmartwrist/moveit_smart_wrist)

[The robot model](https://github.com/fontyssmartwrist/sw_v3_description)

Install guide
=====================================================================
   1) Install MoveIt! kinetic with the following command

	sudo apt install ros-kinetic-moveit

   2) Install MoveIt! TRAC-IK plugin with the following command

	sudo apt-get install ros-kinetic-trac-ik-kinematics-plugin
   
   3) Install rosbridge server with the following command
   
    sudo apt-get install ros-kinetic-rosbridge-server
   
   4) Clone this project and the dependencies to your catkin's workspace src folder
   5) Run catkin_make to build 
    
Documentation
=====================================================================
Documentation how it works can be found in Documentation_on_MoveIt.pdf https://github.com/fontyssmartwrist/smart_movement/blob/master/Documentation_on_MoveIt.pdf  

Web_ROS_CodeSys_Report.pdf

Authors
=====================================================================
Aike van Alkemade

Zhicheng Yu
