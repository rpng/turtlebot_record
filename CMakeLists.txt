cmake_minimum_required(VERSION 2.8.3)
project(turtlebot_record)
find_package(catkin REQUIRED)
catkin_package()

catkin_install_python(PROGRAMS scripts/turtlebot_keyboard DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})