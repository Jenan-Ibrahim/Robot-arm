# Robot-arm

**_1. Install VM with ubuntu 18.04._**

**_2. Install ROS melodic using the commands from "http://wiki.ros.org/melodic/Installation/Ubuntu" site._**

**_3. download robot arm package using:_**
```
$ git clone https://github.com/smart-methods/arduino_robot_arm.git
```
**_4. launch Rvis using the command:_**
```
$ roslaunch robot_arm_pkg check_motors.launch
```
**_5. launch Gazebo using the command:_**
```
$ roslaunch robot_arm_pkg check_motors_gazebo.launch
```
**_6. Control the motors in simulation using:_**
```
$ rosrun robot_arm_pkg joint_states_to_gazebo.py
```
**_7. launch move it set up assistant using:_**
```
$ roslaunch moveit_setup_assistant setup_assistant.launch
```
**_8. launch move it in Rvis using the command:_**
```
$ roslaunch moveit_pkg demo.launch
```
