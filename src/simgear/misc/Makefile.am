includedir = @includedir@/JSBSim/simgear/misc

LIBRARY_SOURCES = sg_path.cxx strutils.cxx

LIBRARY_INCLUDES = sg_path.hxx strutils.hxx stdint.hxx

if BUILD_LIBRARIES
noinst_LTLIBRARIES = libMisc.la
include_HEADERS = $(LIBRARY_INCLUDES)
libMisc_la_SOURCES = $(LIBRARY_SOURCES)
libMisc_la_CXXFLAGS = $(AM_CXXFLAGS)
else
noinst_LIBRARIES = libMisc.a
noinst_HEADERS = $(LIBRARY_INCLUDES)
libMisc_a_SOURCES = $(LIBRARY_SOURCES)
endif

INCLUDES = -I$(top_srcdir)/src -I../
