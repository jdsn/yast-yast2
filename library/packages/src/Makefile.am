# Makefile.am for yast2/library/packages/src

yncludedir = @yncludedir@/packages

YCPCFLAGS = -M ../../modules -M ../../wizard/src -M ../../system/src/ -M ../../types/src -M ../../commandline/src -M ../../xml/src -M ../../control/src -M ../../desktop/src

module_DATA = $(wildcard [[:upper:]]*.ycp)

ynclude_DATA =			\
	common.ycp

packages:
	ln -sf . packages

ycpchook = packages

EXTRA_DIST = $(module_DATA) $(ynclude_DATA)

include $(top_srcdir)/Makefile.am.common
