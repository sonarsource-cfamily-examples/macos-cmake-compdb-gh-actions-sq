cmake_minimum_required(VERSION 3.9)
project(sonar_scanner_example)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

add_executable(sonar_scanner_example src/main.cpp)

