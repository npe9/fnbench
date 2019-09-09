#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.68])
AC_INIT([testfn], [1.0], [noah.evans@gmail.com])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])

AM_PROG_AR
LT_INIT
AC_PROG_RANLIB
AC_CONFIG_SRCDIR([src/fnbench.c])
#AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([
				  Makefile
				   src/Makefile
				   ])


# Checks for programs.
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h])

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_OUTPUT
