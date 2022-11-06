# drone_in_a_cave
The idea of ​​this project is to simulate a drone that flies inside a cave, moving it with the keyboard arrows. In turn, the drone will be able to recognize the distance at which it is located and avoid collisions.

Using simulations of https://github.com/LTU-RAI/gazebo_cave_world and https://github.com/Intelligent-Quads/iq_sim.

This file goes inside the src of the workspace.

Steps to run it: 
cd catkin_ws
source devel/setup.bash
roslaunch drone_in_a_cave cave_world.launch
