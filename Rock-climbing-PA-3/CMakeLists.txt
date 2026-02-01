cmake_minimum_required(VERSION 3.10)

project(RockClimbingTracker)

# Set the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add your source files
add_executable(RockClimbingTracker
    src/main.cpp
    src/ClimbingTracker.cpp
    # Add other source files here
)

# Enable testing (if using Doctest or another testing framework)
enable_testing()
