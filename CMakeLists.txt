cmake_minimum_required(VERSION 3.10)
project(DustDistrict LANGUAGES CXX VERSION 1.0.0)
add_executable(bf bf.cpp)
set_target_properties(bf PROPERTIES CXX_STANDARD 11)
add_executable(dfs dfs.cpp)
set_target_properties(dfs PROPERTIES CXX_STANDARD 11)