cmake_minimum_required(VERSION 3.22.0)
project(homeworks_10_02)

include_directories(resources)
set(MAIN_CPP cppm-homeworks-10-02.cpp)

add_executable(homework_10_02 ${MAIN_CPP})
add_subdirectory(resources)
target_link_libraries(homework_10_02 figure_lib)