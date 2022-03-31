cmake_policy(SET CMP0048 NEW)    
project(test VERSION 0.1.0)      
cmake_minimum_required(VERSION 3.20.4)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/include) 




add_subdirectory(${PROJECT_SOURCE_DIR}/src)

