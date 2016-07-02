warning_flags = -Wall -Wextra -Wshadow
common_cflags = -O2 $(MFLAGS) $(warning_flags)
AM_CFLAGS = -std=c99 $(common_cflags)
AM_CXXFLAGS = -std=c++11 $(common_cflags)

AM_CPPFLAGS = $(VapourSynth_CFLAGS)

lib_LTLIBRARIES = libcnr2.la

libcnr2_la_SOURCES = src/cnr2.c

libcnr2_la_LDFLAGS = -no-undefined -avoid-version $(PLUGINLDFLAGS)
