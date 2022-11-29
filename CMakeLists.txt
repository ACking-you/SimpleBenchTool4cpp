cmake_minimum_required(VERSION 3.12)
project(SimpleBenchTool4cpp)

set(CMAKE_CXX_STANDARD 14)
include_directories(./)

add_executable(SimpleBenchTool4cpp tests/main.cpp)
