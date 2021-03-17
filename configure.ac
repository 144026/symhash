#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([libsymhash], [1.0], [])
AM_INIT_AUTOMAKE(-Wall -Werror foreign)
AC_CONFIG_SRCDIR([src])
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_MACRO_DIRS([m4])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
# AC_PROG_RANLIB
AM_PROG_AR

LT_INIT

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([arpa/inet.h netinet/in.h stdint.h sys/socket.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T
AC_TYPE_UINT8_T

# Checks for library functions.

AC_CONFIG_FILES([Makefile
				 src/Makefile
                 bench/Makefile
                 test/Makefile])
AC_OUTPUT
