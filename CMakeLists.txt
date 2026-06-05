cmake_minimum_required(VERSION 3.14)
project(car_crash_classifier C CXX)
set(CMAKE_CXX_STANDARD 14)

add_subdirectory (lib/glfw)

add_executable(car_crash_classifier src/main.cpp)

target_link_libraries(car_crash_classifier glfw)

