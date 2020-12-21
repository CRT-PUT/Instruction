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
* Open terminal and write command below
* `xdg-open ~/.gazebo/`
* create a folder called `models` if doesn't exist already
* Copy all models from home/catkin_ws/src/luh_youbot_os/luh_youbot_gazebo/worlds/models
* Paste models in ~/.gazebo/models/
* Run simulation `roslaunch luh_youbot_gazebo youbot.launch`  

# 5. ERROR FIX

  ### Error: `[Err] [REST.cc:205] Error in REST request`
  * Fix: 
  * In terminal `sudo gedit  ~/.ignition/fuel/config.yaml`
  * This error can be solved by replacing url: `https://api.ignitionfuel.org` by url: `https://api.ignitionrobotics.org`
  
  
# 5. luh_youbot_os wiki
https://github.com/LUHbots/luh_youbot_os/wiki
