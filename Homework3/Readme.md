export IGN_GAZEBO_RESOURCE_PATH=~/ros2_ws/src/Roboticslab24/Homework3/ros2_iiwa/iiwa_description/gazebo/models:$IGN_GAZEBO_RESOURCE_PATH


launching
ros2 launch iiwa_bringup iiwa.launch.py use_sim:="true"


launching aruco detection:
ros2 launch aruco_ros aruco_detection.launch.py 

