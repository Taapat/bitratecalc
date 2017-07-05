AM_CFLAGS = \
	-Wall

AM_CPPFLAGS = \
	@PYTHON_CPPFLAGS@ \
	-include Python.h

AM_CXXFLAGS = \
	-Wall \
	@ENIGMA2_CFLAGS@

lib_LTLIBRARIES = bitratecalc.la

bitratecalc_la_SOURCES = bitratecalc.cpp

bitratecalc_la_LDFLAGS = -avoid-version -module -shared

