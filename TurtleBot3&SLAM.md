# SmartMethods

Use TurtleBot3 with SLAM approach ro create and save map...

First, I visit the websit https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/ to setup my PC by installing the dependenties of TurtleBot packages.
Then, I started with the simulation process by also installing the simulation packages.
I start out by launching Gazebo so i can launch SLAM in Gazebo simulator. TO do that I opened 4 terminals, one for launching gazebo which will display the simulation of the physical place.

![wafle](https://user-images.githubusercontent.com/85957795/123498429-98807480-d638-11eb-9fbb-5bf289c67f57.png)
![wafle1](https://user-images.githubusercontent.com/85957795/123498446-a7ffbd80-d638-11eb-9d7d-9c1de172ab66.png)


The other terminal is for lunaching SLAM by using RViz and it will display the map for the physical place that is in gazebo. Only the turtlebot that is in the map can't move so we need a third terminal in order to move it.


![wafle2](https://user-images.githubusercontent.com/85957795/123498449-ab934480-d638-11eb-9272-e0a663d00a6b.png)
![wafle3](https://user-images.githubusercontent.com/85957795/123498504-e72e0e80-d638-11eb-9ffe-3dfb51c2ee6f.png)



In the third terminal, I launched the turtlebot key to move the turtlebot so in can navigate te place by using some kind of sensors as so.


![wafle4](https://user-images.githubusercontent.com/85957795/123498506-ee551c80-d638-11eb-9466-c203f23e5648.png)
![wafle5](https://user-images.githubusercontent.com/85957795/123498509-f614c100-d638-11eb-9bd1-079fc94d7d64.png)




After the turtlebot have finished creating tha map for the place we need to save it by using the last terminal.
![wafle6](https://user-images.githubusercontent.com/85957795/123498517-03ca4680-d639-11eb-98bd-1112e520c0bf.png)

Now the map is saved in this pictuer and in this map.yaml file https://github.com/ALbatol/SmartMethods/blob/104fb9a1a129a90219e0f6ddb5f1cedc1f4b0175/map.yaml
![wafle7](https://user-images.githubusercontent.com/85957795/123498519-075dcd80-d639-11eb-949a-2bf219be0c6b.png)


Now i can reopen the simulatores again and the turtlebot won't have to navigate the place again. 
