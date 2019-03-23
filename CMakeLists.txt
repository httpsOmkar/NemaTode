cmake_minimum_required(VERSION 3.13)
project(nema_tode)
set(CMAKE_CXX_STANDARD 11)

file(GLOB NEMA_TODE_ROOT_SRC
        "src/*.h"
        "src/*.cpp"
        )

add_library(nema_tode ${NEMA_TODE_ROOT_SRC})
include_directories(include)
