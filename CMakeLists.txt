cmake_minimum_required(VERSION 3.0)
project(InsertionSort)

set(CMAKE_CXX_STANDARD 11)

add_executable(InsertionSort main.cpp VectorInsertionSort.cpp VectorInsertionSort.h Node.h LinkList.cpp LinkList.h)