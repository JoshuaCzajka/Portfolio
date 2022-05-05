cmake_minimum_required(VERSION 3.21)
project(Portfolio)

set(CMAKE_CXX_STANDARD 14)

add_executable(Portfolio main.cpp Card.cpp Card.h Resource.cpp Resource.h Development.cpp Development.h)
