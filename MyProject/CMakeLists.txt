# Minimum CMake version required
cmake_minimum_required(VERSION 3.10)

# Project name and version
project(MyProject VERSION 1.0)

# Add the library subdirectory
add_subdirectory(src/library)

# Add the main executable
add_executable(MyApp src/main.cpp)

# Link the library to the main executable
target_link_libraries(MyApp PRIVATE MyLibrary)
