cmake_minimum_required(VERSION 3.22.0)
project(resources)

set(RESOURCE_LIB Figure.cpp Parallelogramm.cpp Quadrangle.cpp Quadrangle_all_corners_90.cpp Romb.cpp Square.cpp Triangle.cpp Triangle_bedra_ravny.cpp Triangle_C_90.cpp Triangle_equal_sides.cpp)
add_library(figure_lib STATIC ${RESOURCE_LIB})