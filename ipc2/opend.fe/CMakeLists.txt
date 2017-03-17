project(ipc2_opend_fe)

include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)

add_executable(ipc2_opend_fe main.c opend.h cliargs.c request.c)
target_link_libraries(ipc2_opend_fe apue)