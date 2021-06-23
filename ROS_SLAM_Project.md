# SmartMethods
ROS robot with SLAM approach to create and save a map

This ROS project is about a drive robot that drives to an unknown map. It also implements SLAM on a 2 wheeled differential drive robot to map an unknown environment.
A joystick is used to teleoperate the robot in Gazebo. The map is generated then it's used for autonomous navigation using the ROS Navigation stack.

Fisrt, I have installed all the package and dependencies from https://github.com/devanshdhrafani/diff_drive_bot.git .
Then, I have launched Gazebo as shown.

![project1](https://user-images.githubusercontent.com/85957795/123165090-7215da00-d47c-11eb-9c32-9eddcdf50ecd.png)


After that, I have launched SLAM in different terminal so I can visualize th map, as shown.

![project](https://user-images.githubusercontent.com/85957795/123165198-983b7a00-d47c-11eb-92df-59f19cc941be.png)


Now I started to move the robot by using the keyboard in order to navigate the place, as shown.

![Project4](https://user-images.githubusercontent.com/85957795/123165318-bf924700-d47c-11eb-847b-db1beb0fba91.png)
![proj5](https://user-images.githubusercontent.com/85957795/123165339-c6b95500-d47c-11eb-8d9e-64392e3ff7c5.png)


After the robot have navigate the place now it can save the map and reopen Gazebo and SLAM and select 2D position for the robot. 

![project6](https://user-images.githubusercontent.com/85957795/123165354-cb7e0900-d47c-11eb-9952-f044721fb6da.png)

The map now is saved in the test_map.yaml file and here it's link
https://github.com/ALbatol/SmartMethods/blob/c88b16a1a5a89075eed2f94e2d02ff685de42ed4/test_map.yaml
