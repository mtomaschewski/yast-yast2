#
# Makefile.am for yast2/library/network/src/
#

client_DATA =

ynclude_DATA =

module_DATA = $(wildcard [[:upper:]]*.ycp [[:upper:]]*.pm)

EXTRA_DIST = $(client_DATA) $(ynclude_DATA) $(module_DATA)

# runlevel: Service, wizard: Report, Progress, system: Kernel
YCPCFLAGS = -M ../../types/src -M ../../modules -M ../../runlevel/src -M ../../wizard/src -M ../../cwm/src -M ../../control/src -M ../../xml/src -M ../../commandline/src -M ../../packages/src -M ../../desktop/src -M ../../system/src
include $(top_srcdir)/Makefile.am.common
