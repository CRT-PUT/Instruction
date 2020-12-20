# 1. Install dependencies
* ` sudo apt-get install ros-melodic-qt-build`
* ` sudo apt-get install libnlopt-dev`
* ` sudo apt-get install libboost-all-dev`
* ` sudo apt-get install cmake`
* ` sudo apt install pyqt5-dev-tools`
* ` sudo apt install udo`


# 2. Required ROS Packages  
### control_toolbox
* ` cd ~/catkin_ws/src`
* ` git clone -b melodic-devel https://github.com/ros-controls/control_toolbox.git`
### realtime_tools
* ` cd ~/catkin_ws/src`
* ` git clone -b melodic-devel https://github.com/ros-controls/realtime_tools.git`
* ` cd ..`
* ` catkin_make`



# 3. Install luh_youbot_os
* ` cd ~/catkin_ws/src`
* ` git clone -b melodic-devel https://github.com/LUHbots/luh_youbot_os.git`
* ` cd ..`
* ` catkin_make`

# 4. luh_youbot_os wiki
https://github.com/LUHbots/luh_youbot_os/wiki
