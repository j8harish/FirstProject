cmake_minimum_required(VERSION 3.6)
project(FIrstProject)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp DoSomeFun.cpp DoSomeFun.h)
add_executable(FIrstProject ${SOURCE_FILES})