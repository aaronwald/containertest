cmake_minimum_required(VERSION 3.5.0)
project(ctest VERSION 0.1.0 LANGUAGES C CXX)

add_executable(ctest main.cpp)

include(CTest)
enable_testing()

