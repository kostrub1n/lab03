cmake_minimum_required(VERSION 3.25)

project(formatter_lib)
set(SOURCE_LIB formatter.cpp formatter.h)
add_library(formatter_lib STATIC ${SOURCE_LIB})
