cmake_minimum_required(VERSION 3.5)
project(Social_Cluster)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(Social_Cluster ${SOURCE_FILES})