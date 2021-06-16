# SmartMethods
ROS Installation...


First, I have download the virtualBox in order to can run the ubuntu 18.04 on it.
Then, normally i have downloaded the ubuntu 18.04.
while I'm running the virtualBox I have created a new user with the name "ROS" and selected the ubuntu 18.04 as the virtualBox disk.
After that, the ubuntu was Installed.

Now I can install ROS by using this websit http://wiki.ros.org/kinetic/Installation/Source. Where it has all the instructions and codes to install the ROS. I copied each command and pasted it to the terminal. For instance, the command "sudo apt-get install ros-kinetic-desktop-full" will install the ROS kinetic to my desktop.

After I have installed the ROS kinetic, I toke some of the robot arm packages from the Smart Methods github account using the command "git clone https://github.com/smart-methods/arduino_robot_arm.git". After I have installed the packages I could now launch the robot arm simulator which is Rviz by using the command "roslaunch robot_arm_pkg check_motors.launch". Now after the simulator is launched, I can control and moved the robot arm by using the joint state publisher tool. As it shown in the screenshots pictures.



![robot_arm](https://user-images.githubusercontent.com/85957795/122151523-63219d00-ce68-11eb-9553-79a9ba44eb42.png)

![robot_arm1](https://user-images.githubusercontent.com/85957795/122151538-6b79d800-ce68-11eb-8733-ac3eeed0a1f2.png)

![robot_arm2](https://user-images.githubusercontent.com/85957795/122151548-6fa5f580-ce68-11eb-9f3e-f2ec74892ef6.png)
