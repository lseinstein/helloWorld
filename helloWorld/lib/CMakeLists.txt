set(LIB_SRC hello.c)
add_library(wtfhello ${LIB_SRC})
set_target_properties(wtfhello PROPERTIES OUTPUT_NAME "hihello")
