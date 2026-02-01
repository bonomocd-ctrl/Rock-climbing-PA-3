cmake_minimum_required(VERSION 3.10)
project(Week02Assignment)

enable_testing()

add_executable(runTests
    tests/test_main.cpp
)

add_test(NAME AllTests COMMAND runTests)
