cmake_minimum_required(VERSION 3.12)

project(Program)

include(../../CMake/CommonMacros.txt)

include_directories(../../deps/src/imgui)

SETUP_APP(Program "Program" .)

target_sources(Program PUBLIC ${CMAKE_CURRENT_BINARY_DIR}/../../../deps/src/etc2comp/EtcTool/EtcFile.cpp)
target_sources(Program PUBLIC ${CMAKE_CURRENT_BINARY_DIR}/../../../deps/src/etc2comp/EtcTool/EtcFileHeader.cpp)

target_link_libraries(Program glad glfw EtcLib)