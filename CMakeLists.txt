cmake_minimum_required(VERSION 3.16)

project(DisplayImage VERSION 1.0.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package( OpenCV 4.5.5 REQUIRED )

add_executable(DisplayImage
    main.cpp
)

target_link_libraries( DisplayImage opencv::opencv )