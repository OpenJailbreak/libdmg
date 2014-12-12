dnl Process this file with autoconf to produce a configure script.

AC_PREREQ(2.59)
AC_INIT(libdmg, 1.0)
AC_PROG_CC

AC_CANONICAL_SYSTEM
AC_CONFIG_HEADERS([config.h])

dnl Initialize automake
AM_INIT_AUTOMAKE

dnl this allows us specify individual liking flags for each target
AM_PROG_CC_C_O 

AC_CONFIG_MACRO_DIR([m4])

dnl Initialize Libtool
LT_INIT

dnl Check if Libtool is present
dnl Libtool is used for building share libraries 
AC_PROG_LIBTOOL

PKG_CHECK_MODULES(plist, libplist >= 1.0)
PKG_CHECK_MODULES(crippy, libcrippy-1.0 >= 1.0)
PKG_CHECK_MODULES(hfsplus, libhfsplus-1.0 >= 2.0)

AC_CONFIG_FILES(Makefile tools/Makefile src/Makefile include/Makefile libdmg-1.0.pc)
AC_OUTPUT
