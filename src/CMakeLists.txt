add_executable(run run.c)

target_link_libraries(run allocator)

add_subdirectory(allocator)
