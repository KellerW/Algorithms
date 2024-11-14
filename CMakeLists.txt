cmake_minimum_required(VERSION 3.29)
project(Algorithms)
set(EXECUTABLE_NAME Algorithms)

set(LIBRARY_QUEUE myarray)
set(LIBRARY_LINKEDLIST mylinkedlist)
set(LIBRARY_STACK mystack)
set(LIBRARY_QUEUE myqueue)
set(LIBRARY_TREE mytree)
set(LIBRARY_GRAPH graph)

add_executable(${PROJECT_NAME} src/main.cpp)
target_link_libraries(${PROJECT_NAME} ${LIBRARY_QUEUE})

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED On)
set(CMAKE_CXX_EXTENSIONS Off)
set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})

add_subdirectory(src)
