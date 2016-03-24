# UR5-Inverse-Jacobian-Trajectory-Generator
This package runs on ROS Hydro and can make the virtual UR5 execute a trajectory to a given point.<br />
After running Catkin_make, launch the generator using 'roslaunch assignment1 jacobian.launch'.<br />
Make the robot reach a given point as follows: <br />
"rostopic  pub -1  /setpoint geometry_msgs/Point  --  '0.5 ' '.05 ' '.2 ' <br />

###Note:
*Only the first three links are variable.<br />
*Only the position can be specified (not the orientation)
