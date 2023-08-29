cmake_minimum_required(VERSION 3.21)

project(subproject02 LANGUAGES CXX)

add_library(${PROJECT_NAME} MODULE subproject02.cpp)

install(
    TARGETS ${PROJECT_NAME} LIBRARY DESTINATION project/subproject02
)
