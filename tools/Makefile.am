AM_CFLAGS = -I./include -I../include \
			$(libplist_CFLAGS) \
			$(libhfsplus_CFLAGS) \
			$(libcrippy_CFLAGS) 
			
AM_LDFLAGS = $(libplist_LIBS) \
			$(libhfsplus_LIBS) \
			$(libcrippy_LIBS) 

bin_PROGRAMS = dmg

dmg_SOURCES = dmg.c

dmg_LDADD = libdmg-1.0.la
dmg_CFLAGS = $(AM_CFLAGS)
dmg_LDFLAGS = $(AM_LDFLAGS)