include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)
add_executable(orphan3 orphan3.c)
target_link_libraries(orphan3 apue)