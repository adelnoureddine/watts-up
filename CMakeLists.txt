cmake_minimum_required(VERSION 2.8.4)
project(wattsup)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES wattsup.c util.c config.c globals.c)
add_executable(wattsup ${SOURCE_FILES})