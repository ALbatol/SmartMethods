# SmartMethods
ROS robot with SLAM approach to create and save a map

This ROS project is about a drive robot that drives to an unknown map. It also implements SLAM on a 2 wheeled differential drive robot to map an unknown environment.
A joystick is used to teleoperate the robot in Gazebo. The map generated is then used for autonomous navigation using the ROS Navigation stack.

Fisrt, I have installed all the package and dependencies from https://github.com/devanshdhrafani/diff_drive_bot.git .
Then, I have launched Gazebo as shown.

After that, I have launched SLAM in different terminal so I can visualize th map, as shown.


Now I started to move the robot by using the keyboard in order to navigate the place, as shown.

After the robot have navigate the place now it can save the map and reopen Gazebo and SLAM and select 2D position for the robot, as shown
