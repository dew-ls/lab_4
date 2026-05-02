project(solver_app)
add_library(solver_app STATIC equation.cpp)
target_include_directories(solver_app PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/../formatter_ex_lib ${CMAKE_CURRENT_SOURCE_DIR}/../solver_lib)
target_link_libraries(solver_app PRIVATE formatter_ex solver)
