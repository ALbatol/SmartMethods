# SmartMethods

Use TurtleBot with SLAM approach ro create and save map...

First, I visit the websit https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/ to setup my PC by installing the dependenties of TurtleBot packages.
Then, I started with the simulation process by also installing the simulation packages.
I start out by launching Gazebo so i can launch SLAM in Gazebo simulator. TO do that I opened 4 terminals, one for launching gazebo which will display the simulation of the physical place.


![IMG_0371](https://user-images.githubusercontent.com/85957795/123009007-9ada9880-d3c4-11eb-80cc-a071169d4143.jpg)

The other terminal is for lunaching SLAM by using RViz and it will display the map for the physical place that is in gazebo. Only the turtlebot that is in the map can't move so we need a third terminal in order to move it.

![IMG_0372](https://user-images.githubusercontent.com/85957795/123009147-decd9d80-d3c4-11eb-9f75-8e0bb9873606.jpg)

In the third terminal, I launched the turtlebot key to move the turtlebot so in can navigate te place by using some kind of sensors as so.
![SLAM](https://user-images.githubusercontent.com/85957795/123009062-b2198600-d3c4-11eb-967d-514b2af39736.png)

![IMG_0373 - Copy](https://user-images.githubusercontent.com/85957795/123009160-e42ae800-d3c4-11eb-8a01-0de3eb60f1d1.jpg)
After the turtlebot have finished creating tha map for the place we need to save it by using the last terminal. Now i can reopen the simulatores again and the turtlebot won't have to navigate the place again. 
