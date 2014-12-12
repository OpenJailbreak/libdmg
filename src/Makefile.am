AM_CFLAGS = -I$(top_srcdir)/include \
			$(crippy_CFLAGS) \
			$(hfsplus_CFLAGS) \
			$(plist_CFLAGS) \
			$(zlib_CFLAGS) \
			-arch i386 -arch x86_64
			
AM_LDFLAGS = $(crippy_LIBS) \
			$(hfsplus_LIBS) \
			$(plist_LIBS) \
			$(zlib_LIBS) \
			-arch i386 -arch x86_64

lib_LTLIBRARIES = libdmg-1.0.la
libdmg_1_0_la_CFLAGS = $(AM_CFLAGS)
libdmg_1_0_la_LDFLAGS = $(AM_LDFLAGS)
libdmg_1_0_la_SOURCES = libdmg.c \
						abstractfile.c \
						base64.c \
						checksum.c \
						dmgfile.c \
						dmglib.c \
						filevault.c \
						io.c \
						partition.c \
						udif.c
						