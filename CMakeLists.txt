cmake_minimum_required(VERSION 3.2)

# Configure project
project(seed-cpp-boostasio)

set(CMAKE_BINARY_DIR ${CMAKE_SOURCE_DIR}/bin)

# Include interface
include_directories(${CMAKE_SOURCE_DIR}/interface)

# Add src
add_subdirectory(${CMAKE_SOURCE_DIR}/src)
