cmake_minimum_required(VERSION 3.20)

project(terminal_emulator_build)

add_subdirectory(vulkan_helper)
add_subdirectory(glfw)
add_subdirectory(freetype)
add_subdirectory(terminal_emulator_vulkan_renderer)
add_subdirectory(terminal_emulator)

