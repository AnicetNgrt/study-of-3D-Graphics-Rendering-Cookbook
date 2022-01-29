cmake_minimum_required(VERSION 3.12)

project(Program)

include(../../CMake/CommonMacros.txt)

SETUP_APP(Program "Program" .)

target_link_libraries(Program glad glfw)