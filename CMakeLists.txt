cmake_minimum_required(VERSION 3.15)

set(CMAKE_CXX_STANDARD 17)

set(CMAKE_CXX_STANDARD_REQUIRED on)

project(pshell VERSION 1.0.0)

message("Project Name : ${PROJECT_NAME}")

message("Project Version : ${PROJECT_VERSION}")

add_executable(${PROJECT_NAME} src/main.cpp)

target_include_directories(pshell PRIVATE
    inc
)
