SET(CMAKE_C_COMPILER C:/MinGW/bin/gcc)
SET(CMAKE_CXX_COMPILER C:/MinGW/bin/g++)
cmake_minimum_required(VERSION 3.5)
set(CMAKE_CXX_STANDARD 17)
project("HelloApp" LANGUAGES CXX)
add_executable("HelloAppBinary" "main.cpp")
target_compile_features("HelloAppBinary" PRIVATE "cxx_std_17")
