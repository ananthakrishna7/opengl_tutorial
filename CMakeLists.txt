cmake_minimum_required(VERSION 3.10)
project(opengl_testing VERSION 1.0.0)

include_directories(include)

add_executable(opengl_testing src/main.cpp src/glad.c)

target_link_libraries(opengl_testing glfw)
