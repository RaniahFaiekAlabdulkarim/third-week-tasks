since I have already installed ros noetic already, I started with making the catkin workspace and named it: catkin_ws2. since I had errors in the first one.
then I sourced it.
I started to write the commands from this txt file https://s-m.com.sa/ros.txt
stating with ~/catkin_ws2/src since I want the commands to run inside the workspace.
then I did this command git clone https://github.com/smart-methods/arduino_robot_arm.git to get the packages.
I installed rosdep from the paths.
then I did those commands:
ros noetic move it.
ros noetic joint state publisher 
the gazebo control'
and finally ros controllers.
I launched ros with this command: roslaunch robot_arm_pkg check_motors.launch, and it worked as showed in the output screenshot. screenshot is in issues.
