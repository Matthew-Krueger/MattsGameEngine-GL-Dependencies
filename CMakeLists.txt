cmake_minimum_required(VERSION 3.16.3)

add_subdirectory(GLFW-3.3)
add_subdirectory(GLAD)

include_directories(GLFW-3.3/include)
include_directories(GLAD/include)
