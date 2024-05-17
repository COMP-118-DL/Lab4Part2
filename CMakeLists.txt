cmake_minimum_required(VERSION 3.28)
project(Lab4Part2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Lab4Part2
        main.cpp
        matrix.cpp
        matrix.h)
