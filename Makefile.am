
SUBDIRS = src icons

desktopdir = $(datadir)/applications
desktop_DATA =  awf3.desktop

EXTRA_DIST = $(desktop_DATA) \
	AUTHORS COPYING ChangeLog INSTALL NEWS README autogen.sh \
	awf.desktop awf.spec

rpm: dist
	rpmbuild --clean -ta ${distdir}.tar.gz
