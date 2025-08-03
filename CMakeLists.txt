cmake_minimum_required(VERSION 3.10)

project(Vector3d VERSION 1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)


add_executable(vector3d src/main.cpp src/Vector3d.cpp src/Point3d.cpp)

target_include_directories(vector3d PUBLIC include)

