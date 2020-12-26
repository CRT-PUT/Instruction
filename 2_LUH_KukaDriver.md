# 1. Install dependencies
* ` sudo apt-get update`
* ` sudo apt-get install ros-melodic-qt-build`
* ` sudo apt-get install ros-melodic-qt-build`
* ` sudo apt-get install libnlopt-dev`
* ` sudo apt-get install libboost-all-dev`
* ` sudo apt-get install cmake`
* ` sudo apt-get install pyqt5-dev-tools`
* ` sudo apt-get install udo`
* ` sudo apt-get install ros-melodic-cmake-modules`
* ` sudo apt-get install ros-melodic-tf-conversions`
* ` sudo apt-get install ros-melodic-robot-state-publisher`

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
* ` git clone https://github.com/CRT-PUT/luh_crt_os.git`
* ` cd ..`
* ` catkin_make`

# 4. KUKA atwork Gazeboo setup
* Copy the models from luh_youbot_os/luh_youbot_gazebo/worlds/models
* open terminal and write command below
* `xdg-open ~/.gazebo/models/`
* Paste models in ~/.gazebo/models/
* Run gazebo `roslaunch luh_youbot_gazebo youbot.launch`  
* Run KUKA gazebo controller `roslaunch luh_youbot_controller gazebo_controller.launch`
* follow `https://github.com/LUHbots/luh_youbot_os/wiki/%5BB%5D-Create-a-simple-ROS-Package`
* Run `rosrun my_youbot_pkg my_youbot_node`
* Kuka arm must move

# 5. ERROR Handeling
  * Error: `[Err] [REST.cc:205] Error in REST request`
  * Fix: 
  * In terminal `sudo gedit  ~/.ignition/fuel/config.yaml`
  * This error can be solved by replacing url: `https://api.ignitionfuel.org` by url: `https://api.ignitionrobotics.org`
  
  
# 5. luh_youbot_os wiki
https://github.com/LUHbots/luh_youbot_os/wiki
