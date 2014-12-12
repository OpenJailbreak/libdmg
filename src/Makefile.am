AM_CFLAGS = -I./include -I../include \
			$(libcrippy_CFLAGS) \
			$(libhfsplus_CFLAGS) \
			$(libplist_CFLAGS)
			
AM_LDFLAGS = $(libcrippy_LIBS) \
			$(libhfsplus_LIBS) \
			$(libplist_LIBS)

lib_LTLIBRARIES = libdmg-1.0.la

libdmg_1_0_la_SOURCES = libdmg.c \
						abstractfile.c \
						base64.c \
						checksum.c \
						dmgfile.c \
						filevault.c \
						io.c \
						partition.c \
						udif.c

libdmg_1_0_la_CFLAGS = $(AM_CFLAGS)
libdmg_1_0_la_LDFLAGS = $(AM_LDFLAGS)