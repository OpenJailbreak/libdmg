AM_CFLAGS = -I$(top_srcdir)/include \
			$(plist_CFLAGS) \
			$(hfsplus_CFLAGS) \
			$(crippy_CFLAGS) \
			$(zlib_CFLAGS)
			
AM_LDFLAGS = $(plist_LIBS) \
			$(hfsplus_LIBS) \
			$(crippy_LIBS) \
			$(zlib_LIBS)

bin_PROGRAMS = dmg

dmg_SOURCES = dmg.c $(top_srcdir)/src/resources.c
dmg_CFLAGS = $(AM_CFLAGS)
dmg_LDFLAGS = $(AM_LDFLAGS)
dmg_LDADD = $(top_srcdir)/src/libdmg-1.0.la