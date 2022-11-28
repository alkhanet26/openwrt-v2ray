---
name: Bug report
about: Your device information is needed.
title: ''
labels: ''
assignees: ''

---

Please attach the output of following commands.

```
cat /etc/*release
opkg print-architecture
```

root@OpenWrt:~# cat /etc/*release
DISTRIB_ID='OpenWrt'
DISTRIB_RELEASE='21.02.5'
DISTRIB_REVISION='r16688-fa9a932fdb'
DISTRIB_TARGET='ramips/mt7621'
DISTRIB_ARCH='mipsel_24kc'
DISTRIB_DESCRIPTION='OpenWrt 21.02.5 r16688-fa9a932fdb'
DISTRIB_TAINTS=''
NAME="OpenWrt"
VERSION="21.02.5"
ID="openwrt"
ID_LIKE="lede openwrt"
PRETTY_NAME="OpenWrt 21.02.5"
VERSION_ID="21.02.5"
HOME_URL="https://openwrt.org/"
BUG_URL="https://bugs.openwrt.org/"
SUPPORT_URL="https://forum.openwrt.org/"
BUILD_ID="r16688-fa9a932fdb"
OPENWRT_BOARD="ramips/mt7621"
OPENWRT_ARCH="mipsel_24kc"
OPENWRT_TAINTS=""
OPENWRT_DEVICE_MANUFACTURER="OpenWrt"
OPENWRT_DEVICE_MANUFACTURER_URL="https://openwrt.org/"
OPENWRT_DEVICE_PRODUCT="Generic"
OPENWRT_DEVICE_REVISION="v0"
OPENWRT_RELEASE="OpenWrt 21.02.5 r16688-fa9a932fdb"
root@OpenWrt:~# opkg print-architecture
arch all 1
arch noarch 1
arch mipsel_24kc 10
root@OpenWrt:~#

Error relocating /usr/bin/v2ray: __nanosleep_time64
