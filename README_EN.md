<div align="center">

# ZeroWrt — Multi-Device Firmware for MediaTek Filogic

A third-party OpenWrt firmware project for MediaTek Filogic devices, providing device-specific builds for routers from different vendors.

[![Release](https://img.shields.io/badge/release-20261106-2f6fed?style=flat-square)](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/tag/20261106)
[![Platform](https://img.shields.io/badge/platform-MediaTek%20Filogic-f5a623?style=flat-square)](https://openwrt.org/docs/techref/targets/mediatek)
[![License](https://img.shields.io/badge/license-GPL--3.0-e74c3c?style=flat-square)](LICENSE)

[简体中文](README.md) | English

</div>

---

## Overview

**ZeroWrt** is a third-party OpenWrt firmware project for the MediaTek Filogic platform.

The project aims to support multiple router models from different vendors. It provides device-specific firmware images and integrates commonly used network services, proxy tools, system utilities, and MediaTek platform features.

Each device has its own device configuration and firmware images. **Images are not interchangeable between different models.**

The supported device list may expand over time. Always refer to the actual assets attached to each Release.

## Supported Devices

The **20261106** release currently includes firmware for these six devices:

| Vendor / Brand | Device Model | Available Image Types |
| :--- | :--- | :--- |
| Netcore | N60 Pro | Initramfs, Sysupgrade |
| Ruijie | EW-6000GX Pro | Standard, Stock, Expand, U-Boot Mod |
| Ruijie | RG-X60 New | Standard, Stock, Expand, U-Boot Mod |
| Super Gateway | S20L | Initramfs, Sysupgrade |
| Super Gateway | S20M | Initramfs, Sysupgrade |
| Super Gateway | S20P | Initramfs, Sysupgrade |

> This list is based on the firmware assets attached to the current Release. Image layouts vary by device; not every device provides every layout. Check Release assets for newly supported models.

## Downloads

<badge color="success">Latest release: 20261106</badge>

Visit [ZeroWrt 20261106 Release](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/tag/20261106) for the complete asset list and release notes.

### Netcore N60 Pro

| Image | Purpose | Download |
| :--- | :--- | :---: |
| `initramfs-kernel.bin` | Temporary boot image | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-netcore_n60-pro-initramfs-kernel.bin) |
| `squashfs-sysupgrade.bin` | System upgrade image | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-netcore_n60-pro-squashfs-sysupgrade.bin) |

### Ruijie EW-6000GX Pro

| Layout | Image | Download |
| :--- | :--- | :---: |
| Standard | Initramfs | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-initramfs-kernel.bin) |
| Standard | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-squashfs-sysupgrade.bin) |
| Stock | Initramfs | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-stock-initramfs-kernel.bin) |
| Stock | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-stock-squashfs-sysupgrade.bin) |
| Expand | Initramfs | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-expand-initramfs-kernel.bin) |
| Expand | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-expand-squashfs-sysupgrade.bin) |
| U-Boot Mod | Recovery | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-ubootmod-initramfs-recovery.itb) |
| U-Boot Mod | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-ubootmod-squashfs-sysupgrade.itb) |
| U-Boot Mod | Preloader | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-ubootmod-preloader.bin) |
| U-Boot Mod | BL31 + U-Boot | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-ubootmod-bl31-uboot.fip) |

### Ruijie RG-X60 New

| Layout | Image | Download |
| :--- | :--- | :---: |
| Standard | Initramfs | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-initramfs-kernel.bin) |
| Standard | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-squashfs-sysupgrade.bin) |
| Stock | Initramfs | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-stock-initramfs-kernel.bin) |
| Stock | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-stock-squashfs-sysupgrade.bin) |
| Expand | Initramfs | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-expand-initramfs-kernel.bin) |
| Expand | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-expand-squashfs-sysupgrade.bin) |
| U-Boot Mod | Recovery | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-ubootmod-initramfs-recovery.itb) |
| U-Boot Mod | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-ubootmod-squashfs-sysupgrade.itb) |
| U-Boot Mod | Preloader | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-ubootmod-preloader.bin) |
| U-Boot Mod | BL31 + U-Boot | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-ubootmod-bl31-uboot.fip) |

### Super Gateway S20 Series

| Device | Image | Download |
| :--- | :--- | :---: |
| S20L | Initramfs | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20l-initramfs-kernel.bin) |
| S20L | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20l-squashfs-sysupgrade.bin) |
| S20M | Initramfs | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20m-initramfs-kernel.bin) |
| S20M | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20m-squashfs-sysupgrade.bin) |
| S20P | Initramfs | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20p-initramfs-kernel.bin) |
| S20P | Sysupgrade | [Download](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20p-squashfs-sysupgrade.bin) |

## Features

The following describes the project's integration focus. Actual components and versions may vary by device and Release.

| Category | Components / Features |
| :--- | :--- |
| UI | Argon, Bootstrap, LuCI |
| Proxy | OpenClash, PassWall, Xray |
| DNS | SmartDNS, ChinaDNS-NG, Dnsmasq-Full |
| Network acceleration | MediaTek TurboACC, HNAT, FullCone NAT, BBR |
| Traffic management | EQOS-MTK, SQM Cake |
| Network services | UPnP, DDNS, ACME, WireGuard |
| System tools | ttyd, htop, bash, curl, tcpdump |
| Storage | ext4, NTFS3, exFAT, Btrfs, zram |

## Image Types

| Name | Description |
| :--- | :--- |
| Initramfs | Temporary boot image, commonly used for temporary boot, testing, or recovery. Follow the device-specific flashing guide. |
| Sysupgrade | Firmware image for upgrading a compatible running OpenWrt system. |
| Standard | Standard partition layout. |
| Stock | Image built for the corresponding stock partition / bootloader layout. |
| Expand | Layout intended to provide more usable system space. |
| U-Boot Mod | Images for a compatible modified U-Boot environment; may include Preloader, FIP, Recovery, and Sysupgrade files. |

**Important:** Standard, Stock, Expand, and U-Boot Mod are not available for every device and are not interchangeable. Select images according to the exact device model, hardware revision, bootloader, and partition layout.

## Flashing Notes

1. Confirm the exact device model and hardware revision before flashing.
2. Download firmware only for the matching model. Never cross-flash images between different devices.
3. Verify the current bootloader and partition layout. Images for different layouts must not be mixed.
4. Back up the stock firmware, partitions, and important configuration before first-time flashing. Make sure a recovery method is available.
5. Operations involving Preloader, FIP, or U-Boot carry additional risk. Read the device-specific instructions carefully.
6. Keep the device powered reliably during flashing. Do not disconnect power or force a reboot.

## FAQ

<details>
<summary>Can all devices use the same firmware?</summary>

No. Each device has its own configuration and firmware images. Even devices using the same MediaTek SoC may differ in partition layout, GPIO, wireless calibration data, and port definitions. Download firmware for the exact model.
</details>

<details>
<summary>Why are Stock, Expand, or U-Boot Mod images missing for some devices?</summary>

Bootloaders, partition layouts, and adaptation status vary between devices. The available image types are those actually included in each Release. Do not apply another device's layout to your device.
</details>

<details>
<summary>Should I download Initramfs or Sysupgrade?</summary>

It depends on the device's current system and first-flash procedure. Initramfs is generally used for temporary boot or recovery; Sysupgrade is used to upgrade a compatible running system. Follow the device-specific flashing guide before proceeding.
</details>

## Acknowledgements

- [OpenWrt](https://openwrt.org/)
- [ImmortalWrt](https://github.com/immortalwrt)
- [luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)
- [OpenClash](https://github.com/vernesong/OpenClash)
- [PassWall](https://github.com/xiaorouji/openwrt-passwall)
- [SmartDNS](https://github.com/pymumu/smartdns)
- All upstream open-source projects and device-porting contributors

## License

This project is distributed under the [GNU General Public License v3.0](LICENSE).

## Disclaimer

This firmware is provided "as is", without warranties of any kind. Flashing firmware, modifying partitions, or replacing the bootloader may damage your device, cause data loss, or void your warranty. Understand the risks, verify the exact device model, and make backups before proceeding. Users are responsible for damage caused by selecting an incorrect image or performing improper operations. Please comply with applicable local laws and regulations.

<div align="center">

[Back to top](#zerowrt--multi-device-firmware-for-mediatek-filogic) | [简体中文](README.md)

</div>
