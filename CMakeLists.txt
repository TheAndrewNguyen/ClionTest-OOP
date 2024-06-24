cmake_minimum_required(VERSION 3.28)
project(OOP_Practice)

set(CMAKE_CXX_STANDARD 20)

set(SOURCE_FILES
    src/main.cpp
    src/Book.cpp
    src/Libary.cpp
    src/Libary.h
    src/Book.h
)
add_executable(OOP_Practice ${SOURCE_FILES})

