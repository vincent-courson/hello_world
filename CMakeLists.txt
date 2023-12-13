cmake_minimum_required(VERSION 3.14)
include(CMakeDependentOption)

add_executable(Hello_World src/hello_world.cpp)

install(TARGETS Hello_World RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR})

