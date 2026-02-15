cmake_minimum_required(VERSION 3.31.6)

project(practice)#set name

#set where to store libs
set(LibPath ${PROJECT_SOURCE_DIR}/libs)

#set where to store executable files
set(ExePath ${PROJECT_SOURCE_DIR}/bin)

#set the name of libs
set(Calcu cal)
set(Print pri)

#set subdirectories
 add_subdirectory(Code/Calcu)
 add_subdirectory(Code/Print)
 add_subdirectory(Code/Test1)
 add_subdirectory(Code/Test2)