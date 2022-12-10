cmake_minimum_required(VERSION 3.20)
project(SD_COREML_UI VERSION 0.0.1 LANGUAGES CXX)

add_library(${PROJECT_NAME} STATIC SD_CUI_SRC_DIR)

target_compile_definitions(${PROJECT_NAME} PUBLIC SD_COREML_UI)

