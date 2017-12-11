cmake_minimum_required(VERSION 2.8.3)

include(cmake/HunterGate.cmake)
HunterGate(
    URL "https://github.com/lsolanka/hunter/archive/ros-hunter.tar.gz"
    SHA1 "95b3e78099e819e1bf6bb51898d806db150ac5af"
)

project(angles)

hunter_add_package(catkin)

add_subdirectory(angles)
