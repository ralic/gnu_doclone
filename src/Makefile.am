# doClone - a library and front end for creating or restoring images of GNU/Linux systems.
# Copyright (C) 2013 Joan Lledó <joanlluislledo@gmail.com>
#
# See the file COPYING for copying conditions.

SUBDIRS= ConsoleView

bin_PROGRAMS=doclone

doclone_SOURCES= \
	doclone.cc

doclone_CPPFLAGS = \
	-I$(top_srcdir)/include \
	-I$(top_srcdir)/libdoclone/include \
	-DLOCALEDIR=\"$(localedir)\"

doclone_LDADD = \
	ConsoleView/libdcconsoleview.la \
	$(LIBINTL)
