INCLUDES= -I../lib_mrt/ -I../lib_tdss/
bin_PROGRAMS=master
master_SOURCES=command.c  master.c  process.c  server_check.c
master_LDADD= ../lib_tdss/lib_tdss.a ../lib_mrt/lib_mrt.a -lssl
AUTOMAKE_OPTIONS=foreign
