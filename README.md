## OpenWrt for Rockchip rk3328/rk3399, include Nanopi R2S/R4S
#### ⚠ WARNING: USE IT UNDER YOUR OWN RISK. Non profit use only ⚠ 
[![NanoPi R2S 21.02](https://github.com/anaelorlinski/OpenWrt-NanoPi-R2S-R4S-Builds/actions/workflows/NanoPi-r2s-21.02.yml/badge.svg)](https://github.com/anaelorlinski/OpenWrt-NanoPi-R2S-R4S-Builds/actions/workflows/NanoPi-r2s-21.02.yml)

##### Download: [Releases](https://github.com/anaelorlinski/OpenWrt-NanoPi-R2S-R4S-Builds/releases) or [Actions](https://github.com/anaelorlinski/OpenWrt-NanoPi-R2S-R4S-Builds/actions) \(Login Needed\)
- - -
### Introduction
Those are my customized builds of OpenWrt for FriendlyARM NanoPi R2S / R4S

### Config
- OpenWRT 21.02 Vanilla / Kernel 5.4
- Some ImmortalWRT patches for Rockchip target NanoPi R2S (rk3328) / NanoPi R4S support (rk3399) (avoiding the ones creating kernel oopses)
- NanoPi R2S : r8152 driver v1.11.11 backport from kernel 5.10 + realtek r8169 firmwares package
- NanoPi R4S : r8168 driver for R4S (realtek) instead of kernel r8169 + r8169 firmwares package

### Applications
- A useful set of applications from official OpenWrt package feed
- vpn-routing-policy latest version from https://github.com/stangri/source.openwrt.melmac.net


### Thanks to Original Project:
- [quintus-lab](https://github.com/quintus-lab/OpenWRT-Rockchip)

### License
[MIT](https://github.com/anaelorlinski/OpenWRT-Rockchip/blob/master/LICENSE)
