cmake_minimum_required(VERSION 3.12)

project(Program)

include(../../CMake/CommonMacros.txt)

include_directories(../../deps/src/imgui)

SETUP_APP(Program "Program" .)

target_link_libraries(Program glad glfw assimp)