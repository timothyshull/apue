include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)
add_executable(buf buf.c)
target_link_libraries(buf apue)
add_executable(fgetsfputs fgetsfputs.c)
target_link_libraries(fgetsfputs apue)
add_executable(getcharbug getcharbug.c)
target_link_libraries(getcharbug apue)
add_executable(getcputc getcputc.c)
target_link_libraries(getcputc apue)
add_executable(memstr memstr.c)
target_link_libraries(memstr apue)
add_executable(mkstemp mkstemp.c)
target_link_libraries(mkstemp apue)
add_executable(tempfiles tempfiles.c)
target_link_libraries(tempfiles apue)