cmake_minimum_required(VERSION 3.10)
project(plusar-examples)

include_directories(
    ../include
)

add_definitions(-Wall -pedantic)

add_executable(example-basic example_basic.cpp)
