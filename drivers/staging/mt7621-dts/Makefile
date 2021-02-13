# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_DTB_GNUBEE1)       += gbpc1.dtb
dtb-$(CONFIG_DTB_GNUBEE2)       += gbpc2.dtb
dtb-$(CONFIG_DTB_GNUBEE1_UBOOT) += gbpc-uboot.dtb
dtb-$(CONFIG_DTB_HLK7621A)      += hlk7621a.dtb
dtb-$(CONFIG_DTB_HLK7621A_UBOOT)+= hlk7621a-uboot.dtb

obj-y				+= $(patsubst %.dtb, %.dtb.o, $(dtb-y))
