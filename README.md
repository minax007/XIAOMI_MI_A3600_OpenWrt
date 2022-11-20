[![Build OpenWrt](https://github.com/minax007/XIAOMI_MI_AX3600_OpenWrt/actions/workflows/build_dimfishr_pr.yaml/badge.svg)](https://github.com/minax007/XIAOMI_MI_AX3600_OpenWrt/actions/workflows/build_dimfishr_pr.yaml)
[![release](https://img.shields.io/github/v/release/minax007/XIAOMI_MI_AX3600_OpenWrt.svg)](https://github.com/minax007/XIAOMI_MI_AX3600_OpenWrt/releases)

# OpenWrt for Xiaomi Mi AX3600 (R3600)

Different OpenWrt builds with regular and increased partitioning for AX3600 based on the following repositories:

https://github.com/robimarko/openwrt | https://github.com/dimfishr/openwrt | https://github.com/ansuel/openwrt

![grafik](https://user-images.githubusercontent.com/67478561/202847325-0483eca6-1ac8-4efa-8d24-87f8671e8760.png)

Following packages are already installed, so that you do not need to install them via the command line afterwards: 

Added features | Package names
------------ | -------------
**LuCI GUI** | luci
**LuCI Material Theme** | luci-theme-material 
**LuCI Bandwidth Monitor** | luci-app-nlbwmon
**LuCI SQM (QoS)** | luci-app-sqm
**LuCI Adblock with DNS reporting** | luci-app-adblock & tcpdump & curl
