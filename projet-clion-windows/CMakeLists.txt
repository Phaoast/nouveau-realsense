cmake_minimum_required(VERSION 3.20)
project(projet-clion-windows)
#
set(CMAKE_CXX_STANDARD 14)
#
#include_directories(${CMAKE_SOURCE_DIR}/include)
#link_directories(${CMAKE_SOURCE_DIR}/libraries)
#
#add_executable(hello-realsense-cpp rs-hello-realsense.cpp)
#target_link_libraries(hello-realsense-cpp realsense2.lib)

include_directories(include)
link_directories(libraries)
add_executable(rs-example rs-hello-realsense.cpp)
target_link_libraries(rs-example realsense2.lib)