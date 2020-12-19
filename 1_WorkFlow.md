# 1. Creat the WorkFlow
* Install Ubuntu 18.04.5 LTS (recommended) or higher
  
    ## 1.1. ROS Installation Instruction:
     Ros distro (Version):   
    "Melodic" Recommended for ubuntu 18.04 (Our choice)  
    "Neotic" Recommended for ubuntu 20.04  
    Tutorial: https://wiki.ros.org/melodic/Installation/Ubuntu

    ## 1.2. Creating a catkin workspace
    * Tutorial: http://wiki.ros.org/catkin/Tutorials/create_a_workspace
    * In terminal: 
    * ` sudo apt-get install gedit`
    * ` sudo gedit ~/.bashrc`
    * add below lines at the end of editor:
    * `source ~/catkin_ws/devel/setup.bash`
    * `source /opt/ros/melodic/setup.bash`
    ## 1.3. Visual studio code (VSCode)  
    ### Installation
    * Install from ubuntu software or  https://code.visualstudio.com/Download  
    ### Install below Extentions inside VSCode:  
         Required Extentions:
        * C/C++
        * C++ Intellisense
        * CMake
        * Cmake Tools
        * ROS  
        * Python

         Recommended Extentions:
        * Bracket Pair Colorizer
        * vscode-icons
        * Prettier-code foratter
        * XML Tools
        * YAML
    * File > Open Folder > Catkin_ws/SRC 
# 2. get started with ROS
* http://wiki.ros.org/ROS/Tutorials
