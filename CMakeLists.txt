cmake_minimum_required(VERSION 2.8.3)
project(roch_concert)

find_package(catkin REQUIRED)

catkin_package()

install(DIRECTORY launch param
    DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})
