cmake_minimum_required(VERSION 3.12)

project(imgui)
add_library(imgui STATIC)

target_sources(imgui PRIVATE imgui.cpp imgui_demo.cpp imgui_draw.cpp imgui_widgets.cpp)
target_include_directories(imgui PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
