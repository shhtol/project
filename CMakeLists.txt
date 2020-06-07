CMAKE_MINIMUM_REQUIRED(VERSION 2.8)

PROJECT(lesson4)

set(CMAKE_CXX_FLAGS "-std=c++14")


file(GLOB sources "src/*.cpp")

add_executable(lesson4 ${sources})

target_include_directories(lesson4 PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include) 