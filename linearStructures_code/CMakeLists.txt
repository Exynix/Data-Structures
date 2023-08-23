cmake_minimum_required(VERSION 3.26)
project(linearStructures_code)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(linearStructures_code
        NextAnagram.h
        NextAnagram.hxx
        solve_anagram.cxx)
