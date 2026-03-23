# ROS2 Robotic Arm Simulation

A 7-DOF robotic arm simulation built with ROS2, MoveIt, and Gazebo/Isaac Sim. This project explores modern robotic control stacks by creating a fully simulated manipulator for motion planning and control development.

## Key Features
*   Full ROS2 Control integration for hardware abstraction and real-time control.
*   MoveIt 2 motion planning configured for the 7-DOF arm.
*   Multi-simulator support: Gazebo (Fortress/Harmonic) and NVIDIA Isaac Sim.
*   Compatible with ROS2 Humble and Jazzy distributions.

## Tech Stack
ROS2, MoveIt 2, Gazebo Ignition (GZ), NVIDIA Isaac Sim, URDF, ros2_control

## Getting Started
```bash
# Clone the repository
git clone https://github.com/zoreanuj/ros2-robotic-arm-sim.git
cd ros2-robotic-arm-sim
# Source your ROS2 environment and build
colcon build --symlink-install
source install/setup.bash
# Launch the simulation in Gazebo
ros2 launch bcr_arm_gazebo gazebo.launch.py
```