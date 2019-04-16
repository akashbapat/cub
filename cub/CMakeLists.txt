add_library(cub INTERFACE)
target_link_libraries(cub INTERFACE ${CUDA_LIBRARIES})
target_include_directories(cub INTERFACE ${CMAKE_CURRENT_LIST_DIR})
