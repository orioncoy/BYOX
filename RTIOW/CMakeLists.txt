cmake_minimum_required(VERSION 3.28)
project(RTIOW)

set(CMAKE_CXX_STANDARD 17)

add_executable(RTIOW main.cpp
        global.h
        color.h
        ray.h)
