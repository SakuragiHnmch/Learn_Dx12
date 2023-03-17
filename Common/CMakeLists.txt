file(GLOB SOURCES Src/*.cpp)

add_library(Common STATIC ${SOURCES})

target_include_directories(Common PUBLIC Include)
target_link_libraries(Common dxc)