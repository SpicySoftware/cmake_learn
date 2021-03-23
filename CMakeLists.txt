# Set cmake and project options
cmake_minimum_required(VERSION 3.16 FATAL_ERROR)
project(cmake_learn VERSION 0.1 LANGUAGES CXX)

# Set common settings
set(CMAKE_CXX_STANDARD 17)

# Set binaries and libs path
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/build/bin)
set(LIBRARY_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/build/lib)