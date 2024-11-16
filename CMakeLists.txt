project(MyApp C CXX)
cmake_minimum_required(VERSION 3.3.2)

include(cmake/App.cmake)

set(SOURCES "src/RMXApp.h"
            "src/RMXApp.cpp"
            "src/main.cpp")

add_app("${SOURCES}")