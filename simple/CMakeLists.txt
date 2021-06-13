cmake_minimum_required(VERSION 3.10)
set(CMAKE_C_COMPILER C:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/gcc.exe)
set(CMAKE_CXX_COMPILER C:/mingw-w64/x86_64-8.1.0-posix-seh-rt_v6-rev0/mingw64/bin/g++.exe)
project(simple)

add_executable(app sai.cpp)