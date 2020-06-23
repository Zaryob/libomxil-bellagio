check_PROGRAMS = omxrmtest omxprioritytest

bellagio_LDADD = $(top_builddir)/src/libomxil-bellagio.la
common_CFLAGS = -I$(top_builddir)/test/components/common -I$(top_builddir)/include -I$(top_builddir)/src

omxrmtest_SOURCES = omxrmtest.c omxrmtest.h
omxrmtest_LDADD = $(bellagio_LDADD) -lpthread
omxrmtest_CFLAGS = $(common_CFLAGS)

omxprioritytest_SOURCES = omxprioritytest.c omxprioritytest.h
omxprioritytest_LDADD = $(bellagio_LDADD) -lpthread
omxprioritytest_CFLAGS = $(common_CFLAGS)

