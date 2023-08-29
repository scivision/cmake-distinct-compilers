cmake_minimum_required(VERSION 3.21)

project(subproject01 LANGUAGES C)

add_library(${PROJECT_NAME} MODULE subproject01.c)

install(
    TARGETS ${PROJECT_NAME} LIBRARY DESTINATION project/subproject01
)
