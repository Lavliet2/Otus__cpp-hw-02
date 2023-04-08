cmake_minimum_required(VERSION 3.5)

project(homework_02 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(homework_02 main.cpp
    example.h    example.cpp
    toDoMove.h   toDoMove.cpp
)

install(TARGETS homework_02
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR})
