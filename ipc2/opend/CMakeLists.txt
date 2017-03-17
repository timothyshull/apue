project(ipc2_opend)

include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)

add_executable(ipc2_opend_poll main.c opend.h cliargs.c client.c loop.poll.c request.c)
target_link_libraries(ipc2_opend_poll apue)

add_executable(ipc2_opend_select main.c opend.h cliargs.c client.c loop.select.c request.c)
target_link_libraries(ipc2_opend_select apue)
