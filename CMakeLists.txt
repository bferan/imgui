cmake_minimum_required(VERSION 3.12)

set(SRC ${CMAKE_CURRENT_SOURCE_DIR})

target_sources(armada PRIVATE
    ${SRC}/imgui.h
    ${SRC}/imgui.cpp
    ${SRC}/imconfig.h
    ${SRC}/imgui_internal.h
    ${SRC}/imgui_demo.cpp
    ${SRC}/imgui_draw.cpp
    ${SRC}/imgui_widgets.cpp
    ${SRC}/misc/freetype/imgui_freetype.cpp
    ${SRC}/misc/freetype/imgui_freetype.h
)

target_include_directories(armada PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
