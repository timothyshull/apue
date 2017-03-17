project(datafiles)

include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)

add_executable(getpwnam getpwnam.c)
target_link_libraries(getpwnam apue)

add_executable(strftime strftime.c)
target_link_libraries(strftime apue)