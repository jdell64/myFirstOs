cmake_minimum_required(VERSION 3.6)
project(os_project)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp kernel.cpp)
add_executable(os_project ${SOURCE_FILES})