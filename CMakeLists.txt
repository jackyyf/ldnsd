cmake_minimum_required(VERSION 3.2)
project(ldnsd)

set(SOURCE_FILES src/ldnsd.c)
add_executable(ldnsd ${SOURCE_FILES})