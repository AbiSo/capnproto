cmake_minimum_required(VERSION 3.1)
project("Cap'n Proto Root" CXX)

# make sure using c++11
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# disallow compiler specific C++ extensions
# set(CMAKE_CXX_EXTENSIONS OFF)

add_subdirectory(c++)
