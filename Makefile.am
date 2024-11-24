AUTOMAKE_OPTIONS = foreign

bin_PROGRAMS = my_program
my_program_SOURCES = main.cpp FuncA.cpp FuncA.h

check_PROGRAMS = test_FuncA
test_FuncA_SOURCES = tests/test_FuncA.cpp FuncA.cpp FuncA.h

EXTRA_DIST = debian/control debian/rules debian/changelog debian/copyright

DEB_BUILD_MAINT_OPTIONS = hardening=+all
