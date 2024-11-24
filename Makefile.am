AUTOMAKE_OPTIONS = foreign

bin_PROGRAMS = my_program
my_program_SOURCES = main.cpp FuncA.cpp FuncA.h

EXTRA_DIST = debian/control debian/rules debian/changelog debian/copyright

DEB_BUILD_MAINT_OPTIONS = hardening=+all

dist_tarball = $(top_builddir)/my_program-$(VERSION).tar.gz

.PHONY: all
all:
    $(MAKE) -C $(builddir) my_program
