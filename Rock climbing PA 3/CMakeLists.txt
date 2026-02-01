cmake_minimum_required(VERSION 3.10)

project(RockClimbingTracker)

# Set the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the source files for your project
add_executable(RockClimbingTracker
    src/main.cpp  # Your source files
    src/ClimbingTracker.cpp  # Your other source files
)

# Include Doctest (adjust the path if needed)
include_directories(${CMAKE_SOURCE_DIR}/doctest)

# Add testing support
enable_testing()

# Link any libraries or additional configurations
