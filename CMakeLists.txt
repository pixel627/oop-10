cmake_minimum_required(VERSION 3.28)
project(untitled8)

set(CMAKE_CXX_STANDARD 11)

add_executable(untitled8 main.cpp)

find_package(Qt6 COMPONENTS Widgets REQUIRED)
target_link_libraries(${PROJECT_NAME} PRIVATE Qt6::Widgets)
