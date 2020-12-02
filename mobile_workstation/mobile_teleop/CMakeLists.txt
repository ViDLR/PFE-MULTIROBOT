cmake_minimum_required(VERSION 2.8.3)
project(mobile_)


find_package(catkin REQUIRED COMPONENTS
  urdf
  rospy
  std_msgs
)


catkin_python_setup(
)


catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
