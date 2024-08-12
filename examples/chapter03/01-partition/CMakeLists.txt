cmake_minimum_required(VERSION 3.20.0)
project(Rental
CXX
VERSION 1.0
DESCRIPTION tutorial_project
)
message("top:  CMAKE_SOURCE_DIR = ${CMAKE_SOURCE_DIR}")

add_executable(Rental
               main.cpp
               cars/car.cpp
               # more files in other directories
)
