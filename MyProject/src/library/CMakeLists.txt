# Define the library
add_library(MyLibrary MyLibrary.cpp)

# Specify include directories for this library
target_include_directories(MyLibrary PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
