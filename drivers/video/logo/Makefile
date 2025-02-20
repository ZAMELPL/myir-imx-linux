# SPDX-License-Identifier: GPL-2.0
# Makefile for the Linux logos

obj-$(CONFIG_LOGO)			+= logo.o
obj-$(CONFIG_LOGO_LINUX_MONO)		+= logo_linux_mono.o
obj-$(CONFIG_LOGO_LINUX_VGA16)		+= logo_linux_vga16.o
obj-$(CONFIG_LOGO_LINUX_CLUT224)	+= logo_linux_clut224.o
obj-$(CONFIG_CUSTOMER_LOGO_LINUX_CLUT224)	+= customer_logo_linux_clut224.o
obj-$(CONFIG_LOGO_DEC_CLUT224)		+= logo_dec_clut224.o
obj-$(CONFIG_LOGO_MAC_CLUT224)		+= logo_mac_clut224.o
obj-$(CONFIG_LOGO_PARISC_CLUT224)	+= logo_parisc_clut224.o
obj-$(CONFIG_LOGO_SGI_CLUT224)		+= logo_sgi_clut224.o
obj-$(CONFIG_LOGO_SUN_CLUT224)		+= logo_sun_clut224.o
obj-$(CONFIG_LOGO_SUPERH_MONO)		+= logo_superh_mono.o
obj-$(CONFIG_LOGO_SUPERH_VGA16)		+= logo_superh_vga16.o
obj-$(CONFIG_LOGO_SUPERH_CLUT224)	+= logo_superh_clut224.o

obj-$(CONFIG_SPU_BASE)			+= logo_spe_clut224.o

# How to generate logo's

pnmtologo := scripts/pnmtologo

# Create commands like "pnmtologo -t mono -n logo_mac_mono -o ..."
quiet_cmd_logo = LOGO    $@
	cmd_logo = $(pnmtologo) \
			-t $(patsubst $*_%,%,$(notdir $(basename $<))) \
			-n $(notdir $(basename $<)) -o $@ $<

$(obj)/%_mono.c: $(src)/%_mono.pbm $(pnmtologo) FORCE
	$(call if_changed,logo)

$(obj)/%_vga16.c: $(src)/%_vga16.ppm $(pnmtologo) FORCE
	$(call if_changed,logo)

$(obj)/%_clut224.c: $(src)/%_clut224.ppm $(pnmtologo) FORCE
	$(call if_changed,logo)

$(obj)/%_gray256.c: $(src)/%_gray256.pgm $(pnmtologo) FORCE
	$(call if_changed,logo)

# generated C files
targets += *_mono.c *_vga16.c *_clut224.c *_gray256.c
