# Modify By yourself!
project(Project)
cmake_minimum_required(VERSION 3.21)


# Configurations
include(configure.cmake)
include(amsdk-cmake/Initialize.cmake)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

find_package(Boost REQUIRED)
find_package(OpenSSL REQUIRED)

add_subdirectory(src)
