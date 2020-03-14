cmake_minimum_required(VERSION 3.12)

set(SRC ${CMAKE_CURRENT_SOURCE_DIR})

target_sources(armada PRIVATE
    ${SRC}/imgui.cpp
    ${SRC}/imgui_demo.cpp
    ${SRC}/imgui_draw.cpp
    ${SRC}/imgui_widgets.cpp
)

target_include_directories(armada PRIVATE ${CMAKE_CURRENT_SOURCE_DIR})
