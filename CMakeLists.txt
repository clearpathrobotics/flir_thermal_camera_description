cmake_minimum_required(VERSION 2.8.3)
project(flir_thermal_camera_description)

find_package(catkin REQUIRED COMPONENTS xacro)

catkin_package()

install(
  DIRECTORY meshes urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
