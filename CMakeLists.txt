cmake_minimum_required(VERSION 3.13)
project(Be-Tree)

set(CMAKE_CXX_STANDARD 11)

add_executable(BeTree
        test.cpp
        betree.hpp
        swap_space.cpp
        swap_space.hpp
        backing_store.cpp
        backing_store.hpp
        debug.hpp)