# tactile_msgs
Custom ROS messages for use with the tactile toolbox. This package is subject to change and grow with more iterations.

# Installation
1) Navigate to your ROS 2 workspace. It is recommended to use [Isaac Sim's provided workspace](https://github.com/isaac-sim/IsaacSim-ros_workspaces.git), however this is not required.

2) Clone this repo in the `src` folder of your ROS 2 workspace with `git clone https://github.com/cKohl10/tactile_msgs.git`

3) Build your workspace with `colcon build` in the root directory of your ros workspace.

# Services
 - IndexToPos: Takes in a tactile sensor index as an int and returns a position as a Vector3
