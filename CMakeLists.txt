cmake_minimum_required(VERSION 2.8)

project (ldpServer)

add_compile_options(-std=c++11 -Wall)

add_executable(server main.cpp)