AM_CPPFLAGS = \
	@PYTHON_CPPFLAGS@ \
	-include Python.h

AM_CXXFLAGS = \
	-Wall \
	-fno-exceptions \
	@ENIGMA2_CFLAGS@ \
	@PTHREAD_CFLAGS@

plugindir = $(libdir)/enigma2/python/Plugins/Extensions/BitrateViewer

plugin_LTLIBRARIES = bitratecalc.la

bitratecalc_la_SOURCES = \
	bitratecalc.cpp \
	bitratecalc.h

bitratecalc_la_LDFLAGS = \
	-avoid-version \
	-module \
	-shared


