cmake_minimum_required(VERSION 3.10)
project(cpp_fruit_demo)

set(CMAKE_CXX_STANDARD 17)
add_executable(cpp_fruit_demo main.cpp)
target_link_libraries(cpp_fruit_demo fruit) 