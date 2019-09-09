## Copyright (C) 2006 Free Software Foundation, Inc.
## This Makefile.am is free software; the Free Software Foundation
## gives unlimited permission to copy, distribute and modify it.

bin_PROGRAMS = fnbench fnbenchso fnbenchinl
fnbench_SOURCES = fnbench.c
fnbench_LDADD = libtestfn.a
fnbenchso_SOURCES = fnbenchso.c
fnbenchso_LDADD = libtestfnso.la
fnbenchinl_SOURCES = fnbenchinl.c

noinst_LIBRARIES = libtestfn.a
libtestfn_a_SOURCES = testfn.c

noinst_LTLIBRARIES = libtestfnso.la
libtestfnso_la_SOURCES = testfnso.c