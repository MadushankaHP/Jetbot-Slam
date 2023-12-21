# Jetbot-Slam

This project utilizes the TurtleBot3 SLAM ROS package along with the JetBot ROS AI kit for robotic mapping.

**Prerequisites**

Ensure the following prerequisites are installed before using the project:

1. ROS (Robot Operating System) - [Installation Guide](https://wiki.ros.org/Installation).
2. TurtleBot3 - - [Installation Guide](https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/)

**Setup**

1. Clone this repository to your ROS workspace:

   ```bash
   git clone https://github.com/MadushankaHP/Jetbot-Slam.git
   
2. Build the ROS workspace:
   ```bash
   cd your_ros_workspace
   catkin_make
   source devel/setup.bash
   ```

**Usage**

Launch the jetbot slam node:
   ```bash
   roslaunch jetbot_slam slam_run.launch
  ```
Additionally, a demo video is available [here](https://youtu.be/sztuQsBxTBY).
