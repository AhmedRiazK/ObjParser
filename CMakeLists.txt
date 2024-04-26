cmake_minimum_required(VERSION 3.10)

project(parser)

set(CMAKE_SYSTEM_NAME Linux)
set(CMAKE_SYSTEM_PROCESSOR x86)

add_executable (parser parser.cpp)