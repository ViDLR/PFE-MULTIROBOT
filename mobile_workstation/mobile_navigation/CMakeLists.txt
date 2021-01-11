cmake_minimum_required(VERSION 2.8.3)
project(mobile_navigation)


find_package(catkin REQUIRED COMPONENTS
  roscpp
  rospy
  std_msgs
nav_msgs
)



catkin_package(
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
