cmake_minimum_required(VERSION 3.20)
project(SD_CUI)

set(CMAKE_CXX_STANDARD 23)

find_package(OpenGL REQUIRED)

set(DEPENDENCIES_SRC_DIR ${PROJECT_SOURCE_DIR}/third_party)
set(DEPENDENCIES_BIN_DIR ${PROJECT_BINARY_DIR}/third_party)
set(SD_CUI_SRC_DIR ${PROJECT_SOURCE_DIR}/sdcui)

add_subdirectory(SD_COREML_UI)
add_subdirectory(Thirdparty)
