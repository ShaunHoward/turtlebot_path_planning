# turtlebot_rrt
Path planning with the Turtlebot using various RRT algorithms from ompl.

# installation instructions
- first, install ros indigo (latest turtlebot capable version), make sure to run: echo "source /opt/ros/indigo/setup.bash" >> ~/.bashrc and source the .bashrc
- then run: sudo apt-get install libsdformat1 gazebo2 ros-indigo-turtlebot ros-indigo-turtlebot-apps ros-indigo-turtlebot-interactions ros-indigo-turtlebot-simulator ros-indigo-kobuki-ftdi ros-indigo-rocon-remocon ros-indigo-rocon-qt-library ros-indigo-ar-track-alvar-msgs
restart shell for changes to take effect

# run robot simulator and planner
- catkin_make
- roslaunch turtlebot_rrt start_rrt_benchmark.launch
