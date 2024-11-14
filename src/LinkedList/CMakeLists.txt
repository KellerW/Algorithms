set(LIBRARY_SOURCES "MyLinkedList.cpp")
set(LIBRARY_HEADERS "MyLinkedList.hpp")

add_library(${LIBRARY_LINKEDLIST} STATIC
    ${LIBRARY_SOURCES}
    ${LIBRARY_HEADERS})
    target_include_directories(${LIBRARY_LINKEDLIST} PUBLIC "./")