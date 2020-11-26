# Ateks ROS Noetic 
This repository includes the Ateks ROS Noetic packages.

![Image of Ateks](https://github.com/inomuh/ateks/blob/main/ateks.png)

- ateks_description: It is the subpackage containing urdf files of the Ateks.
- ateks_simulation: It is a sub-package containing the package and launch files required for the simulation of the Ateks.

Gazebo Launching:

    $ roslaunch ateks_simulation ateks_empty_world.launch

Solo-Rviz Launching:

    $ roslaunch ateks_simulation ateks_rviz_standalone.launch
    
Rviz (with Gazebo) Launching:

    $ roslaunch ateks_simulation ateks_rviz.launch
    
   
------------------------------------------------------------------------------
Requirements:
-------------
- In order for the "joint_state_publisher" to work, "joint_state_publisher_gui" package must be downloaded to your computer.

        $ sudo apt update
        $ sudo apt install ros-noetic-joint-state-publisher-gui
        
-------------------------------------------------------------------------------
Changelog:
----------
Update v1.0 - 26.11.20
----------------------
- First version
