cmake_minimum_required(VERSION 3.23)
project(learn_dx12)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_WIN32_EXECUTABLE TRUE)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/Common/Include)

add_subdirectory(Chapters)
add_subdirectory(Common)
add_subdirectory(3rd)