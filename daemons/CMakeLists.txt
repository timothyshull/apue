project(daemons)

include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)

add_executable(init init.c)
target_link_libraries(init apue)

add_executable(reread reread.c)
target_link_libraries(reread apue)

add_executable(reread2 reread2.c)
target_link_libraries(reread2 apue)

add_executable(single single.c)
target_link_libraries(single apue)