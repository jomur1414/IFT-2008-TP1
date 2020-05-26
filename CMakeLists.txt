cmake_minimum_required(VERSION 3.5)
project(CodeTP1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    ListeCirculaire.h
    ListeCirculaire.hpp
    Principal.cpp
    Regle.cpp
    Regle.h
    SystemeExpert.cpp
    SystemeExpert.h)

add_executable(CodeTP1 ${SOURCE_FILES})