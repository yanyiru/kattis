# cmake_minimum_required(VERSION <specify CMake version here>)
project(kattis C)

set(CMAKE_C_STANDARD 99)

add_executable(kattis main.c quadrantSelection.c)