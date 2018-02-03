cmake_minimum_required(VERSION 3.6)
project(MorfiConvertv0)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES library.cpp library.h)
add_library(MorfiConvertv0 ${SOURCE_FILES})