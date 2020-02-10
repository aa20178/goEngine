cmake_minimum_required(VERSION 3.0.0)
project(goEngine)

add_executable(engineExe
 src/main.cpp
 src/hello.cpp
 )

 target_include_directories(engineExe PRIVATE include)