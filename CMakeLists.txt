cmake_minimum_required(VERSION 3.21)
project(interpreter)

set(CMAKE_CXX_STANDARD 14)

add_executable(interpreter main.cpp bitsStdcpp.h)
