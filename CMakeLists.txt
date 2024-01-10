cmake_minimum_required(VERSION 3.12.4)

project(robot VERSION 0.1.0)

add_executable(robot main.c)

message("robot is installed in \"${CMAKE_INSTALL_PREFIX}/sbin\"")

install(TARGETS robot DESTINATION ${CMAKE_INSTALL_PREFIX}/sbin)