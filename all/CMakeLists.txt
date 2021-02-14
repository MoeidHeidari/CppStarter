cmake_minimum_required(VERSION 3.14 FATAL_ERROR)

project(BuildAll LANGUAGES CXX)

include(../cmake/tools.cmake)

add_subdirectory(${CMAKE_CURRENT_LIST_DIR}/.../app ${CMAKE_BINARY_DIR}/app)
add_subdirectory(${CMAKE_CURRENT_LIST_DIR}/../test ${CMAKE_BINARY_DIR}/test)
add_subdirectory(${CMAKE_CURENT_LIST_DIR}/../documentation ${CMAKE_BINARY_DIR}/documentation)
