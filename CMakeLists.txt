cmake_minimum_required(VERSION 3.10)

set(project-name primes_in_range)
project(${project-name} VERSION 1.0)
cmake_policy(SET CMP0048 NEW)

set(CMAKE_CXX_STANDARD 14)


add_executable(${project-name}
        main.cpp
        primes_in_range.cpp
        primes_in_range.hpp
        primes.cpp
        primes.hpp)