cmake_minimum_required(VERSION 3.15)

# Project name and language
project(sleepyFox VERSION 0.0.1 LANGUAGES CXX)

# C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(sleepyFox
    src/hello_world.cpp
)

# Add include directory
target_include_directories(sleepyFox
    PUBLIC
        ${PROJECT_SOURCE_DIR}/include)
