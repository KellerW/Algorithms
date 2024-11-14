set(LIBRARY_SOURCES "MyStack.cpp")
set(LIBRARY_HEADERS "MyStack.hpp")

add_library(${LIBRARY_STACK} STATIC
    ${LIBRARY_SOURCES}
    ${LIBRARY_HEADERS})
    target_include_directories(${LIBRARY_STACK} PUBLIC "./")