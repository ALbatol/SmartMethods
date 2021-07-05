# SmartMethods
Using SLAM map to launch the navigation 

First, I went to https://emanual.robotis.com/docs/en/platform/turtlebot3/nav_simulation/ and copied the commands to launch gazebo. 
Then, I have opned a new terminal in order to launch the turtlebot3 navigator by opening the map.yaml file which is got the map saved in it, as shown.


![nav](https://user-images.githubusercontent.com/85957795/124513299-2865b180-dde3-11eb-986c-bf35cb530853.png)

After that, I have opened a third terminal to run the command "ristopic echo /move_base_simple/goal" in order to determine the position and the orientation. 
Then, i clicked on 2D Nav Goal and picked a target point that the turtlebot should head for automariclally.

![nav1](https://user-images.githubusercontent.com/85957795/124513312-2e5b9280-dde3-11eb-80d1-6bf946862853.png)

Finally, the turtlebot will determine the shortest path and walk throught it till it reach to the target point without any guiding, as shown.

![nav3](https://user-images.githubusercontent.com/85957795/124513707-11738f00-dde4-11eb-8c77-2576e39fcad4.png)
![nav4](https://user-images.githubusercontent.com/85957795/124513711-16384300-dde4-11eb-90ac-1572d2370871.png)

