cmake_minimum_required(VERSION 3.16)
project(helloworld)
include(GNUInstallDirs)
add_executable(${CMAKE_PROJECT_NAME} src/hello.c)
install(TARGETS helloworld
        RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR})
