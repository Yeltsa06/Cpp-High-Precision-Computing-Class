cmake_minimum_required(VERSION 3.11)
project(BigInt)

include_directories(./includes)

add_compile_definitions(CMAKE)

add_executable(BigInt ./src/main.cpp)