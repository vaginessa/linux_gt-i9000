#
# Makefile for RIO switches
#

obj-$(CONFIG_RAPIDIO_TSI57X)	+= tsi57x.o
obj-$(CONFIG_RAPIDIO_CPS_XX)	+= idtcps.o
obj-$(CONFIG_RAPIDIO_TSI568)	+= tsi568.o
obj-$(CONFIG_RAPIDIO_TSI500)	+= tsi500.o

ifeq ($(CONFIG_RAPIDIO_DEBUG),y)
EXTRA_CFLAGS += -DDEBUG
endif
