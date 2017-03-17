project(advio)

include_directories(${libapue_SOURCE_DIR} ${apue_SOURCE_DIR}/include)

add_executable(deadlock deadlock.c)
target_link_libraries(deadlock apue)

add_executable(lockfile lockfile.c)
target_link_libraries(lockfile apue)

add_executable(mandatory mandatory.c)
target_link_libraries(mandatory apue)

add_executable(mcopy2 mcopy2.c)
target_link_libraries(mcopy2 apue)

add_executable(nonblockw nonblockw.c)
target_link_libraries(nonblockw apue)

add_executable(advio_readn readn.c)
target_link_libraries(advio_readn apue)

add_executable(rot13a rot13a.c)
target_link_libraries(rot13a apue)

add_executable(rot13c2 rot13c2.c)
target_link_libraries(rot13c2 apue)

#add_executable(advio_writen writen.c)
#target_link_libraries(advio_writen apue)