cmake_minimum_required(VERSION 3.20)

project(
    Lumen
    VERSION 0.1.0
    DESCRIPTION "Lumen Graphics Framework"
    LANGUAGES CXX
)

# Use C++23
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

# Create the executable
add_executable(Lumen
    src/main.cpp
)

# Include header files
target_include_directories(Lumen PRIVATE include)
