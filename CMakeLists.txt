cmake_minimum_required(VERSION 3.27)

project(Frem VERSION 0.0.1 LANGUAGES C CXX)

set(BOOST_ROOT "D:/boost")
find_package(Boost REQUIRED)

include_directories(${Boost_INCLUDE_DIRS})

add_executable(Frem src/main.cpp)