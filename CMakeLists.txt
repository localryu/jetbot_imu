cmake_minimum_required(VERSION 2.8.3)
project(jetbot_imu)

# add_compile_options(-std=c++11)

find_package(catkin REQUIRED COMPONENTS
  rospy
  std_msgs
  mavros
  #message_generation
)

# find_package(Boost REQUIRED COMPONENTS system)

# catkin_python_setup()

catkin_package(
   
#  INCLUDE_DIRS include
#  LIBRARIES gmsl
#   CATKIN_DEPENDS message_runtime
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)
