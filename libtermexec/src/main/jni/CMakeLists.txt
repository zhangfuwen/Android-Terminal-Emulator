
cmake_minimum_required(VERSION 3.2)

project(libjackpal-termexec2)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -O3")

add_library(jackpal-termexec2 PUBLIC proccess.cpp)