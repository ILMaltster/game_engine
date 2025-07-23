cmake_minimum_required(VERSION 3.13 FATAL_ERROR)

project(GameEngine)

add_executable(GameEngine src/main.cpp)

add_subdirectory(external/glfw)
target_link_libraries(GameEngine GLFW)