bin_PROGRAMS = mbchk
bin_SCRIPTS = grub-image mkbimage
sbin_SCRIPTS = grub-install grub-md5-crypt grub-terminfo \
	grub-set-default

# XXX: Need to search for a header file in docs, because of multiboot.h.
AM_CFLAGS = -I$(top_srcdir)/lib -I$(top_srcdir)/docs

mbchk_SOURCES = mbchk.c
mbchk_LDADD = ../lib/libcommon.a
