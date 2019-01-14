cmake_minimum_required(VERSION 3.12)
project(Master)

set(CMAKE_CXX_STANDARD 14)

include_directories(.idea)
include_directories(cmake-build-debug)

add_executable(Master
        .idea/codeStyles/Project.xml
        .idea/Master.iml
        .idea/misc.xml
        .idea/modules.xml
        .idea/vcs.xml
        .idea/workspace.xml
        cmake-build-debug/cmake_install.cmake
        cmake-build-debug/CMakeCache.txt
        cmake-build-debug/Makefile
        cmake-build-debug/Master.cbp
        CMakeLists.txt
        main.c)
