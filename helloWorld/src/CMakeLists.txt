include_directories(${PROJECT_SOURCE_DIR}/wtfhello)
set(SRC_LIST main.c)
add_executable(hello ${SRC_LIST})
target_link_libraries(hello wtfhello)
