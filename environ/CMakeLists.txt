include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)
add_executable(cmd1 cmd1.c)
target_link_libraries(cmd1 apue)
add_executable(cmd2 cmd2.c)
target_link_libraries(cmd2 apue)
add_executable(doatexit doatexit.c)
target_link_libraries(doatexit apue)
add_executable(echoarg echoarg.c)
target_link_libraries(echoarg apue)
add_executable(getrlimit getrlimit.c)
target_link_libraries(getrlimit apue)
add_executable(hello1 hello1.c)
target_link_libraries(hello1 apue)
add_executable(opendata opendata.c)
target_link_libraries(opendata apue)
add_executable(scope scope.c)
target_link_libraries(scope apue)
add_executable(testjmp testjmp.c)
target_link_libraries(testjmp apue)