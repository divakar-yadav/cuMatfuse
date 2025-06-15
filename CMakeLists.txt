cmake_minimum_required(VERSION 3.18)
project(cuMatfuse LANGUAGES CXX CUDA)

set(CMAKE_CXX_STANDARD 14)
enable_language(CUDA)

include_directories(include)

add_executable(cuMatfuse_demo src/main.cpp src/cuMatfuse_kernel.cu)
