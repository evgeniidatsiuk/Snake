cmake_minimum_required(VERSION 3.15)
project(Snake)

set(OpenGlLinkers -lglut -lGLU -lGL)
set(CMAKE_CXX_STANDARD 17)

add_executable(Snake main.cpp)
target_link_libraries(Snake ${OpenGlLinkers})