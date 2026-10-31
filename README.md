# My Journey with TP-Link xx530v V2

Starting from the official firmware, I managed to port OpenWrt to this router and bring up a fully functional OpenWrt-based system. The work included adding support for the optical link path in three parts: the laser driver, the GPON MAC/PHY driver, and the userspace configuration layer responsible for device setup.

In parallel, I also enabled hardware offload acceleration for traffic processing by implementing the first generation of WED support, a mechanism also used in older routers such as MT7621. This effort also improved the hardware-assisted WED behavior on mt7916 and helped reduce bufferbloat.

[Read the test wiki page](wiki/test.html)
