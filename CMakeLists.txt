cmake_minimum_required(VERSION 3.12)

project(hello CXX)

set(SRCS
    src/hello.cpp
)

add_executable(${PROJECT_NAME} ${SRCS})
