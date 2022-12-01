cmake_minimum_required(VERSION 3.19)

# project info
project(Namir LANGUAGES CXX)
set (PROJECT_NAME_SHORT  "Namir")
set (PROJECT_NAME_LONG   "Namir project manager")
set (PROJECT_DESCRIPTION "CMake build system template for Qt based projects")
set (PROJECT_COPYRIGHT   "Copyright (C) 2022 Andrij Felenko")
set (PROJECT_CONTACT     "andrij.felenko@tuta.io")
set (PROJECT_VENDOR      "Andrij Felenko")
set (ORG_WEBSITE         "http://namir.io")

# build info
set (CMAKE_AUTOMOC ON)
set (CMAKE_AUTOUIC ON)
set (CMAKE_AUTORCC ON)
set (CMAKE_CXX_STANDARD 20)
#set (CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin/app)
#set (CMAKE_LIBRARY_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin/lib)
#set (CMAKE_ARCHIVE_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin/archive)

# subdirs
add_subdirectory (app)
add_subdirectory (libs)
add_subdirectory (server)
