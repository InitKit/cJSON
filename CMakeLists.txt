add_library(ik-cjson cJSON.c cJSON_Utils.c)
target_include_directories(ik-cjson PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})