cmake_minimum_required(VERSION 3.11)
project(simdb)

set(CMAKE_CXX_STANDARD 11)

include_directories(.)

add_executable(simdb
        ConcurrentMap.cpp
        simdb.hpp)
