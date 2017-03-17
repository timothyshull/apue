project(db)

include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)

add_library(apue_db apue_db.h db.c)
target_link_libraries(apue_db apue)

add_executable(t4 t4.c)
target_link_libraries(t4 apue)