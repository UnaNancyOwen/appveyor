cmake_minimum_required( VERSION 2.8 )

project( solution )
add_executable( project main.cpp )
set_property( DIRECTORY PROPERTY VS_STARTUP_PROJECT "project" )