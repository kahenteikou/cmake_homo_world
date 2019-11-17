cmake_minimum_required(VERSION 3.0)

project(cmake_homo_world)

add_executable(cmake_homo_world main.cpp)

install(TARGETS cmake_homo_world RUNTIME DESTINATION bin)
