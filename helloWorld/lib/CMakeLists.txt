set(LIB_SRC hello.c)
add_library(wtfhello ${LIB_SRC})
set(LIBRARY_OUTPUT_PATH ${PROJECT_BINARY_DIR}/lib)
set_target_properties(wtfhello PROPERTIES OUTPUT_NAME "hihello")
