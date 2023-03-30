cmake_minimum_required(VERSION 3.26.1)
project(main1)


add_executable(main1 main.cpp)
target_include_directories(main1 PRIVATE geometry_lib)