# temp. solution while mailcheck & xdcc arn't in SUBDIRS
EXTRA_DIST = Make.plugin plugin-conf.in xdcc/xdcc.c xdcc/Makefile.am

# noinst_HEADERS = hexchat-plugin.h

if DO_PYTHON
pythondir = python
endif

if DO_PERL
perldir = perl
endif

if DO_DOAT
doatdir = doat
endif

if DO_FISHLIM
fishlimdir = fishlim
endif

if DO_CHECKSUM
checksumdir = checksum
endif

if DO_SYSINFO
sysinfodir = sysinfo
endif

#SUBDIRS = . $(pythondir) $(perldir) mailcheck xdcc
SUBDIRS = . $(pythondir) $(perldir) $(checksumdir) $(doatdir) $(fishlimdir) $(sysinfodir)
