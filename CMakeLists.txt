cmake_minimum_required(VERSION 3.19)
project(CPU_Monitor)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(CPU_Monitor
        main.cpp)
