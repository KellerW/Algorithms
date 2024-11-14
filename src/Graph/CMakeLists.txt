set(LIBRARY_SOURCES "MyGraph.cpp")
set(LIBRARY_HEADERS "MyGraph.hpp")

add_library(${LIBRARY_GRAPH} STATIC
    ${LIBRARY_SOURCES}
    ${LIBRARY_HEADERS})
    target_include_directories(${LIBRARY_GRAPH} PUBLIC "./")