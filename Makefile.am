## Process this file with automake to produce Makefile.in
## Created by Anjuta

SUBDIRS = src 

tmmdsreaderdocdir = ${prefix}/doc/tmmdsreader
tmmdsreaderdoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


EXTRA_DIST = $(tmmdsreaderdoc_DATA)


# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(tmmdsreaderdocdir)
