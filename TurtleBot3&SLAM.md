# SmartMethods

Use TurtleBot with SLAM approach ro create and save map...

First, I visit the websit https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/ to setup my PC by installing the dependenties of TurtleBot packages.
Then, I started with the simulation process by also installing the simulation packages.
I start out by launching Gazebo so i can launch SLAM in Gazebo simulator. TO do that I opened 4 terminals, one for launching gazebo which will display the simulation of the physical place. The other terminal is for lunaching SLAM by using RViz and it will display the map for the physical place that is in gazebo. Only the turtlebot that is in the map can't move so we need a third terminal in order to move it. In the third terminal, I launched the turtlebot key to move the turtlebot so in can navigate te place by using some kind of sensors. After the turtlebot have finished creating tha map for the place we need to save it by using the last terminal. Now i can reopen the simulatores again and the turtlebot won't have to navigate the place again. 