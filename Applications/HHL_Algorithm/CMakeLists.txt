cmake_minimum_required(VERSION 3.1)
project(HHL_Algorithm)
file(GLOB_RECURSE HHL_CPP ${CMAKE_CURRENT_SOURCE_DIR}/*.cpp )
add_executable(${PROJECT_NAME} ${HHL_CPP})
target_link_libraries(${PROJECT_NAME} ${LIB_QPANDA})
