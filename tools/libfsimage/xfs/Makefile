XEN_ROOT = $(CURDIR)/../../..

LIB_SRCS-y = fsys_xfs.c

FS = xfs

.PHONY: all
all: fs-all

.PHONY: install
install: fs-install

.PHONY: uninstall
uninstall: fs-uninstall

include $(XEN_ROOT)/tools/libfsimage/Rules.mk
