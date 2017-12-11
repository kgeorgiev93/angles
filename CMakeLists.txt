cmake_minimum_required(VERSION 2.8.3)

include(cmake/HunterGate.cmake)
HunterGate(
    URL "https://github.com/ruslo/hunter/archive/v0.23.207.tar.gz"
    SHA1 "6e1b05a1f65c2aa492f7f43a43578e83ac62bbdd"
)

project(angles)

hunter_add_package(catkin)

add_subdirectory(angles)
