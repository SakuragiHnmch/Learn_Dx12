cmake_minimum_required(VERSION 3.23)
project(learn_dx12)

set(CMAKE_CXX_STANDARD 14)

file(GLOB sources src/*.cpp)

add_executable(learn_dx12 ${sources})
