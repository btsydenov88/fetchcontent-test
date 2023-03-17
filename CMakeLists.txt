cmake_minimum_required(VERSION 3.17)
project(untitled2)

set(CMAKE_CXX_STANDARD 17)

add_executable(untitled2 main.cpp)

include(FetchContent)
FetchContent_Declare(
        cmake-examples
        GIT_REPOSITORY git@github.com:btsydenov88/testrepo.git
)

FetchContent_MakeAvailable(cmake-examples)
