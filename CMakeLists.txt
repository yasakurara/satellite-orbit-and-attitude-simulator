if(${CMAKE_SOURCE_DIR} STREQUAL ${CMAKE_BINARY_DIR})
  message(FATAL_ERROR "DO NOT BUILD in-tree.")
endif()

cmake_minimum_required(VERSION 3.23.1)
project(satellite-orbit-and-attitude-simulator)
add_subdirectory(src)