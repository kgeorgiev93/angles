cmake_minimum_required(VERSION 2.8.3)

include(cmake/HunterGate.cmake)
HunterGate(
    URL "https://github.com/ruslo/hunter/archive/v0.23.28.tar.gz"
    SHA1 "6c79b36253a8e8bcba48927e9f3be65a3a81e6ec"
)

project(angles)

hunter_add_package(catkin)

add_subdirectory(angles)
