cmake_minimum_required(VERSION 3.7)
project(DebugLogger)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -o3 -std=c++11  -msse2 -msse3 -msse4 -lopencv_aruco -lpthread -lSophus ")

set(SOURCE_FILES main.cpp)
add_executable(DebugLogger ${SOURCE_FILES})