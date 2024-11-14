set(LIBRARY_SOURCES "MyTree.cpp")
set(LIBRARY_HEADERS "MyTree.hpp")

add_library(${LIBRARY_TREE} STATIC
    ${LIBRARY_SOURCES}
    ${LIBRARY_HEADERS})
    target_include_directories(${LIBRARY_TREE} PUBLIC "./")