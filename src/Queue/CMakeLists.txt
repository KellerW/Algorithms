set(LIBRARY_SOURCES "MyQueue.cpp")
set(LIBRARY_HEADERS "MyQueue.hpp")

add_library(${LIBRARY_QUEUE} STATIC
    ${LIBRARY_SOURCES}
    ${LIBRARY_HEADERS})
    target_include_directories(${LIBRARY_QUEUE} PUBLIC "./")