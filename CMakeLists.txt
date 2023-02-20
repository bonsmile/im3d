cmake_minimum_required( VERSION 3.16.0 )

project(im3d)

add_library(im3d STATIC
	im3d_config.h
	im3d_math.h
	im3d.h
	im3d.cpp
)
