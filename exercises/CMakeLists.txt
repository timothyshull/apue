include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)
add_executable(asyncsocket asyncsocket.c)
target_link_libraries(asyncsocket apue)
add_executable(bo bo.c)
target_link_libraries(bo apue)
add_executable(fifo1 fifo1.c)
target_link_libraries(fifo1 apue)
add_executable(fmemopen fmemopen.c)
target_link_libraries(fmemopen apue)
add_executable(getlogin getlogin.c)
target_link_libraries(getlogin apue)
add_executable(getpw44bsd getpw44bsd.c)
target_link_libraries(getpw44bsd apue)
add_executable(getpwsvr4 getpwsvr4.c)
target_link_libraries(getpwsvr4 apue)
add_executable(goodexit goodexit.c)
target_link_libraries(goodexit apue)
add_executable(longpath longpath.c)
target_link_libraries(longpath apue)
add_executable(exercises_openmax openmax.c)
target_link_libraries(exercises_openmax apue)
add_executable(pendlock pendlock.c)
target_link_libraries(pendlock apue)
add_executable(pollmsg2 pollmsg2.c)
target_link_libraries(pollmsg2 apue)
add_executable(prtime prtime.c)
target_link_libraries(prtime apue)
add_executable(sizepipe sizepipe.c)
target_link_libraries(sizepipe apue)
add_executable(exercises_sleep sleep.c)
target_link_libraries(exercises_sleep apue)
add_executable(sleepus_poll sleepus_poll.c)
target_link_libraries(sleepus_poll apue)
add_executable(sleepus_select sleepus_select.c)
target_link_libraries(sleepus_select apue)
add_executable(vfork3 vfork3.c)
target_link_libraries(vfork3 apue)
add_executable(zombie zombie.c)
target_link_libraries(zombie apue)