cmake_minimum_required(VERSION 3.20.0)
project(Rental
CXX
VERSION 1.0
DESCRIPTION tutorial_project
)
add_executable(Rental
               main.cpp
               cars/car.cpp
               # more files in other directories
)
