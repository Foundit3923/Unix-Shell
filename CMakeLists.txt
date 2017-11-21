cmake_minimum_required(VERSION 3.8)
project(code_shell)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c)
add_executable(code_shell ${SOURCE_FILES})