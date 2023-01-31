cmake_minimum_required(VERSION 3.23)
project(jack)

set(CMAKE_CXX_STANDARD 14)

include_directories(src)

add_executable(jack
        src/jack.cpp
        src/jack.h)
