cmake_minimum_required(VERSION 3.11 FATAL_ERROR)
project(ExternalResources)

set(CMAKE_CXX_STANDARD 17)

add_library(stb_image_lib STATIC stb_image/stb_file.cpp)