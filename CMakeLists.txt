cmake_minimum_required(VERSION 3.21)
project(webServer)

set(CMAKE_CXX_STANDARD 14)

add_executable(webServer main.cpp threadPool.h http.h http.cpp locker.h)
