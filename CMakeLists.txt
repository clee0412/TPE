cmake_minimum_required(VERSION 3.23)
project(TPE)

set(CMAKE_C_STANDARD 99)

add_executable(TPE main.c getnum.h getnum.c random.h random.c utilist.h utilist.c tp11_ej14.h)

set(CMAKE_C_FLAGS "-Wall -pedantic -std=c99 -lm -fsanitize=address")
