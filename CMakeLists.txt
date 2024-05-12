cmake_minimum_required (VERSION 3.13)

project (ToDoApp)

set (CMAKE_CXX_STANDARD 20)
set (CMAKE_CXX_COMPILER clang++)

set (SOURCES "src/main.cc")

add_executable(${PROJECT_NAME} ${SOURCES})

target_include_directories (${PROJECT_NAME} PRIVATE src)
