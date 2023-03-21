file(GLOB SOURCES Src/*.cpp)

add_library(Common ${SOURCES})

#target_include_directories(Common PUBLIC Include)
target_link_libraries(Common PUBLIC d3dcompiler d3d12 dxgi)

target_compile_definitions(Common PUBLIC UNICODE)