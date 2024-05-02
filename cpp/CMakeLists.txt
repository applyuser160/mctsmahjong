cmake_minimum_required(VERSION 3.13)

project(test)

set(CMAKE_CXX_STANDARD 23)

SET(CMAKE_CXX_FLAGS  "-Ofast")

add_executable(a.out main.cpp)

add_library(abc STATIC main.cpp)