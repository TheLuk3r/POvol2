cmake_minimum_required(VERSION 3.8)
project(POvol2)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Portfel.h Aktywo.cpp Aktywo.h lokata.cpp lokata.h)
add_executable(POvol2 ${SOURCE_FILES})