cmake_minimum_required(VERSION 3.10)
project(stringify C)

set(CMAKE_C_STANDARD 90)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall -Wextra -Werror -pedantic -pedantic-errors")

# archive
include_directories(sources)

# examples
include(examples/build.cmake)
