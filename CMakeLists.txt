cmake_minimum_required(VERSION 3.21)
project(Database-From-Scratch)
set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED On)
set(CMAKE_CXX_EXTENSIONS Off)

set(CMAKE_CXX_FLAGS_DEBUG "${CMAKE_CXX_FLAGS_DEBUG} -g -Werror -pedantic-errors -Wall -Weffc++ -Wextra -Wconversion")
set(SOURCE src/main.cpp)
add_executable(DatabaseFromScratch ${SOURCE})