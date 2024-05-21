cmake_minimum_required(VERSION 3.15)

add_library(silver-bun INTERFACE)
target_include_directories(silver-bun INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/silver-bun)