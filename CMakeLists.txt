cmake_minimum_required(VERSION 3.19)
project(lab1 C)

set(CMAKE_C_STANDARD 99)

include_directories(.)

add_executable(lab1
        complex.c
        complex.h
        functions.c
        functions.h
        main.c
        math.c
        math.h
        matrix.c
        matrix.h
        menu.c
        menu.h
        test.c
        test.h)
