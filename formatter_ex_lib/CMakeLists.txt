project(formatter_ex)
add_library(formatter_ex STATIC formatter_ex.cpp formatter_ex.h)
target_include_directories(formatter_ex PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/../formatter_lib)
target_link_libraries(formatter_ex PUBLIC formatter)
