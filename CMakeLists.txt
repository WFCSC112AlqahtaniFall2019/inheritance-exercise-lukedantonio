cmake_minimum_required(VERSION 3.0)
project(inheritance)

set(CMAKE_CXX_STANDARD 11)

add_executable(inheritance main.cpp Polygon.cpp Polygon.h Rectangle.h Rectangle.cpp Triangle.h Triangle.cpp)