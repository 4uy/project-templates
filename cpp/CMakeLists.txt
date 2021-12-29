cmake_minimum_required(VERSION 3.5)

project(project)

set(CMAKE_CXX_STANDARD 20)

file(GLOB_RECURSE SOURCES RELATIVE ${CMAKE_SOURCE_DIR} "src/*.cc" "src/*/*.cc")
add_executable(${PROJECT_NAME} ${SOURCES})