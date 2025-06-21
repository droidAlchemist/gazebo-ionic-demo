# Gazebo Ionic Demo
## Ionic demo world and resources

cd ~/gazebo-ionic-demo/ros2_ws/
colcon build

source install/setup.bash

## Example

```
cd ~/gazebo-ionic-demo/ros2_ws/src/ionic_demo/worlds
gz sim -v 4 ionic.sdf
```

## Launch files 

ros2 launch ionic_demo ionic_navigation_demo_launch.py headless:=0

ros2 launch ionic_demo world_launch.py headless:=0

