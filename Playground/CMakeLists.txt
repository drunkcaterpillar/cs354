cmake_minimum_required(VERSION 3.21)
project(Playground C)

set(CMAKE_C_STANDARD 11)

add_executable(Reverse reverse.c)
add_executable(DynamicArray dynamic_array.c)
add_executable(Transpose transpose.c)
add_executable(Structs Structs.c)
