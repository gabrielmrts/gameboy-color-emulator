cmake_minimum_required(VERSION 3.24)

project(gameBoyEmu CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(gameBoyEmu src/main.cpp)