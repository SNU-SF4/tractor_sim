cmake_minimum_required(VERSION 2.8.3)
project(tractor_sim_description)
find_package(catkin REQUIRED)
catkin_package()

install(DIRECTORY launch urdf DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
