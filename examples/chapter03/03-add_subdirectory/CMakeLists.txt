cmake_minimum_required(VERSION 3.20.0)
project(Rental CXX)

add_executable(Rental main.cpp)

add_subdirectory(cars EXCLUDE_FROM_ALL)     
target_link_libraries(Rental PRIVATE cars)
