This project is inherited from [GantBot](https://github.com/wisnukusuma/GantBot/tree/main), using the robot_only.urdf.xacro then loaded it to MoveIt setup assistance.
build it first
```
cd ~/[your development workspace]
colcon build --symlink-install
source install/setup.bash
```
To run it, run the following command
```
ros2 launch gantry_moveit_config demo.launch.py
```
