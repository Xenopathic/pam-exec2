AC_INIT([pam-exec2], [0.5], [rmccorkell@karoshi.org.uk])
AC_PREREQ([2.61])

AC_CONFIG_SRCDIR([src/pam_exec2.c])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_FILES([Makefile])
AC_DISABLE_STATIC

AC_PROG_CC
AC_PROG_INSTALL

AM_INIT_AUTOMAKE([subdir-objects])
LT_INIT

AC_ARG_ENABLE(securedir,
	AS_HELP_STRING([--enable-securedir=DIR],[path to location of PAMs @<:@default=$libdir/security@:>@]),
	SECUREDIR=$enableval, SECUREDIR=$libdir/security)
AC_SUBST(SECUREDIR)

AC_OUTPUT
