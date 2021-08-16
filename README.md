# gazebo_ros_vacuum_gripper_debugger

This is ROS package for checking the execution status of GazeboRosVacuumGripper plugin

## Installation

    $ cd ~/catkin_ws/src
    $ git clone https://github.com/tatsuya-s/gazebo_ros_vacuum_gripper_debugger
    $ cd ~/catkin_ws/
    $ catkin build

## Usage

### Run gazebo

    $ roslaunch gazebo_ros_vacuum_gripper_debugger test_gazebo.launch

### Grasp box

    $ rosservice call /vacuum_gripper/on

### Check grasping state

    $ rostopic echo /vacuum_gripper/grasping
    $ CTRL+c

## Author

Tatsuya Sakuma <sakuma.tatsuya.sn1@is.naist.jp>
