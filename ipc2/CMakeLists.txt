project(ipc2)

include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)

add_executable(bindunix bindunix.c)
target_link_libraries(bindunix apue)

add_executable(pollmsg pollmsg.c)
target_link_libraries(pollmsg apue)

add_executable(recvfd2 recvfd2.c)
target_link_libraries(recvfd2 apue)

add_executable(sendfd2 sendfd2.c)
target_link_libraries(sendfd2 apue)

add_executable(sendmsg sendmsg.c)
target_link_libraries(sendmsg apue)

add_subdirectory(open)
add_subdirectory(open.fe)
add_subdirectory(opend)
add_subdirectory(opend.fe)