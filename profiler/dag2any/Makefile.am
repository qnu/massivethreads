
# required when you use libtool (for building shared libs)
ACLOCAL_AMFLAGS = -I m4

bin_PROGRAMS = dag2any
dag2any_SOURCES = dag2any.c
dag2any_CFLAGS = -I$(abs_top_srcdir)/profiler -DDAG_RECORDER=2
dag2any_LDFLAGS = -L$(abs_top_builddir)/profiler -Wl,-R$(abs_top_builddir)/profiler -ldr @LIBSQLITE3@

