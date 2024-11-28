cmake_minimum_required(VERSION 3.10)

project("lab21")

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_CXX_EXTENSIONS OFF)

include_directories(${CMAKE_SOURCE_DIR})

add_executable(lab21 main.cpp 1prog.cpp 2prog.cpp)

set_target_properties(lab21 PROPERTIES 
    RUNTIME_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}/bin"
)
