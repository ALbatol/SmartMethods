# SmartMethods
ROS Installation...


First, I have download the virtualBox in order to can run the ubuntu 18.04 on it.
Then, normally i have downloaded the ubuntu 18.04.
while I'm running the virtualBox I have created a new user with the name "ROS" and selected the ubuntu 18.04 as the virtualBox disk.
After that, the ubuntu was Installed.

Now I can install ROS by using this websit http://wiki.ros.org/melodic/Installation/Ubuntu. Where it has all the instructions and codes to install the ROS. I copied each command and pasted it to the terminal. For instance, the command "sudo apt install ros-melodic-desktop-full" will install the ROS melodic to my desktop.

Robot Arm Configuration...


After I have installed the ROS melodic, I toke some of the robot arm packages from the Smart Methods github account using the command "git clone https://github.com/smart-methods/arduino_robot_arm.git". After I have installed the packages I could now launch the robot arm simulator which is Rviz by using the command "roslaunch robot_arm_pkg check_motors.launch". Now after the simulator is launched, I can control and moved the robot arm, as it shown in the screenshots pictures.



 
