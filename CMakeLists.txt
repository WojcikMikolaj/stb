cmake_minimum_required(VERSION 3.28)

set(CMAKE_CXX_STANDARD 23)

set(CMAKE_CXX_SCAN_FOR_MODULES OFF)

add_library(stb_image
        stb_image.cpp
        stb_image.h
        )