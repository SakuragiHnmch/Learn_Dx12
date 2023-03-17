cmake_minimum_required(VERSION 3.23)
project(learn_dx12)

set(CMAKE_CXX_STANDARD 14)

file(GLOB sources src/*.cpp)

include_directories(3rd/DirectXHeaders/include)
include_directories(3rd/dxc/include)

link_directories(3rd/dxc/lib)

add_subdirectory(Chapters)
add_subdirectory(Common)