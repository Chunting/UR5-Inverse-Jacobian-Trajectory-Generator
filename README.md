# UR5-Inverse-Jacobian-Trajectory-Generator
This package runs on ROS Hydro and can make the virtual UR5 execute a trajectory to a given point.
After running Catkin_make, launch the generator using 'roslaunch assignment1 jacobian.launch'
Make the robot reach a given point as follows: 
"rostopic  pub -1  /setpoint geometry_msgs/Point  --  '0.5 ' '.05 ' '.2 '

###Note:
*Only the first three links are variable.
*Only the position can be specified (not the orientation)
