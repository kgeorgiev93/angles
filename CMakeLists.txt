cmake_minimum_required(VERSION 2.8.3)

include(cmake/HunterGate.cmake)
HunterGate(
    URL "https://github.com/lsolanka/hunter/archive/v0.19.210-11.tar.gz"
    SHA1 "ae63309e76bcad9748e236a28dc9fbd217811482"
)

project(angles)

hunter_add_package(ros-catkin)

add_subdirectory(angles)
