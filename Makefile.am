AUTOMAKE_OPTIONS = foreign

bin_PROGRAMS = my_program
my_program_SOURCES = main.cpp FuncA.cpp FuncA.h

EXTRA_DIST = control rules changelog copyright

DEB_BUILD_MAINT_OPTIONS = hardening=+all
AM_INIT_AUTOMAKE([foreign])

dist_tarball = $(top_builddir)/my_program-$(VERSION).tar.gz
