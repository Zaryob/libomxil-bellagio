check_PROGRAMS = omxvolcontroltest omxaudiomixertest

bellagio_LDADD = $(top_builddir)/src/libomxil-bellagio.la
common_CFLAGS = -I$(top_builddir)/test/components/common -I$(top_builddir)/include -I$(top_builddir)/src

omxvolcontroltest_SOURCES = omxvolcontroltest.c omxvolcontroltest.h
omxvolcontroltest_LDADD = $(bellagio_LDADD) -lpthread 
omxvolcontroltest_CFLAGS = $(common_CFLAGS)

omxaudiomixertest_SOURCES = omxaudiomixertest.c omxaudiomixertest.h
omxaudiomixertest_LDADD = $(bellagio_LDADD) -lpthread
omxaudiomixertest_CFLAGS = $(common_CFLAGS)
