pkglibexecdir = $(libexecdir)/@PACKAGE@
pkglibexec_PROGRAMS = mixw_interp

mixw_interp_SOURCES = cmd_ln_defn.h main.c parse_cmd_ln.c parse_cmd_ln.h 

LDADD = \
	$(top_builddir)/src/libs/libio/libio.la \
	$(top_builddir)/src/libs/libmodinv/libmodinv.la \
	$(top_builddir)/src/libs/libcommon/libcommon.la \
	$(top_builddir)/src/libs/libclust/libclust.la \
	$(top_builddir)/src/libs/libmllr/libmllr.la

INCLUDES = -I$(top_srcdir)/include

