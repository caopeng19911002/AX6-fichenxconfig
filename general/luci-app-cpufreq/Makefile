
# Copyright (C) 2016 Openwrt.org
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI for CPU Freq Setting
LUCI_DEPENDS:=@(arm||aarch64)
#LUCI_DEPENDS:=@TARGET_armvirt_64
PKG_NAME:=luci-app-cpufreq
PKG_VERSION:=1
PKG_RELEASE:=6

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
