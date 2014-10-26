cmake_minimum_required(VERSION 3.0)

project(treet
	VERSION 0.0.1
	LANGUAGES C CXX)

include_directories(.)
set(CMAKE_CXX_FLAGS "-ggdb3 -std=c++11")
set(CMAKE_C_FLAGS   "-ggdb3 -std=c99")

add_subdirectory("ext")
add_subdirectory("src")
