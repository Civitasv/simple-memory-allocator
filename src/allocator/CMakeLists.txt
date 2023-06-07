add_library(allocator allocator.c)

target_link_libraries(allocator md4c)

target_include_directories(allocator PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

