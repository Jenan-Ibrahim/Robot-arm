# Robot-arm

**1. Install VM with ubuntu 18.04**

**2. Install ROS melodic using the commands from "http://wiki.ros.org/melodic/Installation/Ubuntu" site**

**3. download robot arm package using:**
```
$ git clone https://github.com/smart-methods/arduino_robot_arm.git
```
**4. launch Rvis using the command:**
```
$ roslaunch robot_arm_pkg check_motors.launch
```
**5. launch Gazebo using the command:**
```
$ roslaunch robot_arm_pkg check_motors_gazebo.launch
```
**6. Control the motors in simulation using:**
```
$ rosrun robot_arm_pkg joint_states_to_gazebo.py
```
**7. launch move it set up assistant using:**
```
$ roslaunch moveit_setup_assistant setup_assistant.launch
```
**8. launch move it in Rvis using the command:**
```
$ roslaunch moveit_pkg demo.launch
```
