cmake_minimum_required(VERSION 3.10 FATAL_ERROR)

set(CMAKE_INSTALL_LIBDIR ${CMAKE_INSTALL_PREFIX}/lib)
set(CMAKE_INSTALL_BINDIR ${CMAKE_INSTALL_PREFIX}/bin)
set(CMAKE_INSTALL_INCLUDEDIR ${CMAKE_INSTALL_PREFIX}/include)

add_subdirectory(libGraph)
add_subdirectory(drawLine)
add_subdirectory(miniPaint)
