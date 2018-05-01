# husky_simualtor

## Version
* Based on [`indigo-devel` branch of `husky`](https://github.com/Shentheman/husky/tree/irg) and [`indigo-devel` branch of `husky_simulator`](https://github.com/husky/husky_simulator), we have built our own fork with [`irg` branch of `husky`](https://github.com/Shentheman/husky) and [`irg` branch of `husky_simulator`](https://github.com/Shentheman/husky_simulator)
  - Note that the newest release, e.g. [0.3.0 of `husky`](https://github.com/husky/husky/releases) is for ROS Kinetic


## Meshes
* We are using the original meshes [`husky_simulator/husky_gazebo/urdf/description.gazebo.xacro`](https://github.com/husky/husky_simulator/blob/indigo-devel/husky_gazebo/urdf/description.gazebo.xacro)


## Tutorials
* http://www.clearpathrobotics.com/assets/guides/ros/Getting%20Started%20with%20Ubuntu.html
* http://wiki.ros.org/husky_navigation/Tutorials


## Navigation
- `roslaunch husky_gazebo husky_empty_world.launch`
- `roslaunch husky_viz view_robot.launch`
- `roslaunch husky_navigation move_base_mapless_demo.launch`
- Use `2D navigation goal` in RVIZ
