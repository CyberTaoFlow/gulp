cmake_minimum_required(VERSION 3.10.2)
project(gulp)

set(CMAKE_C_FLAGS "-O")

add_executable(gulp gulp.c)
target_link_libraries(gulp pthread pcap)
