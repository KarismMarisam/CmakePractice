cmake_minimum_required(VERSION 3.31.6)

project(practice)#set name

set(EXECUTABLE_OUTPUT_PATH ..)#set the directory to store final executable file(including shared libary),notice that current directory is Makefile's

include_directories(Libraries)#search xx.h in specific directories

link_directories(Libraries)#set the direcory to search libraries

add_executable(result main.cpp)

target_link_libraries(result libCal.so)