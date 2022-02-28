add_library(bitop STATIC bit.c)
target_include_directories(bitop PRIVATE ${LUA_INCLUDE_DIR})
