# Use ROS Robot with SLAM
**This Repository will explain my 3rd task in Robotics and AI department at [SMART METHODS](https://github.com/smart-methods) summer training.**

## Task Requirements: 
  - Use another ROS robot to creat and save a map.
  
## Detailed Steps:
1. Using this package to provide a simulation environment of a warehouse. A robot is simulated at the center of the environment, with 2D laser scanner provided. 


2. Install ROS package `sudo apt-get install ros-melodic-hector-trajectory-server ros-melodic-slam-gmapping ros-melodic-navigation
`
3.Clone repository
   - `cd ~/catkin_ws/src`
   - `git clone https://github.com/mo7ammed-saleh/warehouse_simulation_toolkit`
   - `cd ..`
   - `catkin_make`
   - `source ~/catkin_ws/devel/setup.bash`

4. Launch ROS
    - `roslaunch warehouse_simulation warehouse_simulation.launch`
     <p align='center'><img width="80%" src="https://github.com/mo7ammed-saleh/Use_ROS_Robot_with_SLAM/blob/main/Robot%20Environment.png"/>
     </p>
     
     
5. Autonomous Navigation by setting a target points in RVIZ and the robot will navigate to the location in gazebo. 
   - click 2d nav goal button on rviz and then click any points you want on the map.
   - 
   <p align='center'><img width="80%" src="https://github.com/mo7ammed-saleh/Use_ROS_Robot_with_SLAM/blob/main/Navigation.png"/>
     </p>
   -
   <p align='center'><img width="80%" src="https://github.com/mo7ammed-saleh/Use_ROS_Robot_with_SLAM/blob/main/Point%20navigation.gif"/>
     </p>
     
6. Refrences: (https://github.com/Amg0z/warehouse_simulation_toolkit).
7. Task is Done :heart_eyes:
