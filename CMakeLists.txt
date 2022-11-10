cmake_minimum_required(VERSION 3.23)
project(microml)

set(CMAKE_CXX_STANDARD 17)

add_executable(microml_test_quarter_float src/test_quarter_float.cpp src/quarter_float.hpp src/unit_test.hpp)

