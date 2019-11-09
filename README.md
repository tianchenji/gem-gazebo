# Gem-gazebo
## Quick start
1. clone this repo
2. `catkin_make` and `source`
3. run `roslaunch test_gazebo first_world.launch` to launch the gazebo
4. run `rosrun polaris_control gem_controller.py` to start the controller
## Waypoints follower
The vehicle can now follow predetermined waypoints. Desired waypoints can be edited by changing `ref_x` and `ref_y` variables in `GetOffset.py` under `polaris_control` directory. 
