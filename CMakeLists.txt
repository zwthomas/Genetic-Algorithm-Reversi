cmake_minimum_required(VERSION 3.8)
project(GA_Reversi)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        Board.cpp
        Board.h
        CMakeLists.txt
        Game.cpp
        Game.h
        Heuristic.cpp
        Heuristic.h
        main.cpp
        Triple.cpp
        Triple.h)

add_executable(GA_Reversi ${SOURCE_FILES})