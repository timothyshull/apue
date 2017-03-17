project(ipc2_open)

include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)

add_executable(ipc2_open main.c open.h open.c)
target_link_libraries(ipc2_open apue)
