cmake_minimum_required(VERSION 3.20)

# IMGUI
add_subdirectory(imgui)
set_target_properties(imgui PROPERTIES FOLDER "Dependencies")

# GLFW
set(GLFW_BUILD_EXAMPLES OFF)
set(GLFW_BUILD_TESTS OFF)
set(GLFW_BUILD_DOCS OFF)
set(GLFW_INSTALL OFF)
set(GLFW_VULKAN_STATIC OFF)
add_subdirectory(glfw)
set_target_properties(glfw PROPERTIES FOLDER "Dependencies")
