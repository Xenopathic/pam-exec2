ACLOCAL_AMFLAGS = -I m4

AM_CFLAGS = -std=c99

securelibdir = $(SECUREDIR)

securelib_LTLIBRARIES = pam_exec2.la

pam_exec2_la_SOURCES = src/pam_exec2.c
pam_exec2_la_CFLAGS = $(AM_CFLAGS) -D _GNU_SOURCE
pam_exec2_la_LIBADD = -lpam -lcap -lpam-once
pam_exec2_la_LDFLAGS = -module -avoid-version
