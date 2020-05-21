include $(top_srcdir)/build/modmake.rulesam
MODNAME=mod_janus

mod_LTLIBRARIES = mod_janus.la
mod_janus_la_SOURCES  = mod_janus.c globals.c cJSON.c http.c api.c servers.c hash.c
mod_janus_la_CFLAGS   = $(AM_CFLAGS)
mod_janus_la_LIBADD   = $(switch_builddir)/libfreeswitch.la
mod_janus_la_LDFLAGS  = -avoid-version -module -no-undefined -shared
