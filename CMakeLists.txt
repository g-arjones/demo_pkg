cmake_minimum_required(VERSION 3.5)
project(demo_pkg)
add_executable(demo_main main.cpp)
install(TARGETS demo_main DESTINATION bin)
