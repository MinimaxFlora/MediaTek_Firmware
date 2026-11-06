<div align="center">

# ZeroWrt — MediaTek Filogic 多设备固件

面向 MediaTek Filogic 平台的第三方 OpenWrt 固件项目，为不同厂商、不同型号的路由设备提供适配固件。

[![Release](https://img.shields.io/badge/release-20261106-2f6fed?style=flat-square)](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/tag/20261106)
[![Platform](https://img.shields.io/badge/platform-MediaTek%20Filogic-f5a623?style=flat-square)](https://openwrt.org/docs/techref/targets/mediatek)
[![License](https://img.shields.io/badge/license-GPL--3.0-e74c3c?style=flat-square)](LICENSE)

简体中文 | [English](README_EN.md)

</div>

---

## 项目简介

**ZeroWrt** 是一个面向 MediaTek Filogic（联发科 Filogic）平台的第三方 OpenWrt 固件项目。

项目以多设备适配为目标，为不同品牌和型号的路由器提供对应的固件镜像，并整合常用网络服务、代理工具、系统管理组件及 MediaTek 平台相关功能。每个设备使用独立的设备配置和镜像，**不同型号之间不可混刷**。

本仓库的设备支持范围会随 Release 持续更新。请以每个版本 Release 中实际上传的固件文件为准。

## 支持设备

**Release 20261106** 当前包含以下 6 款设备：

| 厂商 / 品牌 | 设备型号 | 当前提供的镜像类型 |
| :--- | :--- | :--- |
| Netcore（磊科） | N60 Pro | Initramfs、Sysupgrade |
| Ruijie（锐捷） | EW-6000GX Pro | 标准、原厂、扩容、U-Boot Mod |
| Ruijie（锐捷） | RG-X60 New | 标准、原厂、扩容、U-Boot Mod |
| Super Gateway | S20L | Initramfs、Sysupgrade |
| Super Gateway | S20M | Initramfs、Sysupgrade |
| Super Gateway | S20P | Initramfs、Sysupgrade |

> 设备列表根据本次 Release 的实际固件附件整理。镜像布局因设备而异，并非每款设备都提供全部布局。后续新增机型请关注 Release 附件。

## 下载固件

<badge color="success">最新版本：20261106</badge>

前往 [ZeroWrt 20261106 Release](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/tag/20261106) 查看完整文件列表和版本说明。

### Netcore N60 Pro

| 镜像 | 用途 | 下载 |
| :--- | :--- | :---: |
| `initramfs-kernel.bin` | 临时启动镜像 | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-netcore_n60-pro-initramfs-kernel.bin) |
| `squashfs-sysupgrade.bin` | 系统升级镜像 | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-netcore_n60-pro-squashfs-sysupgrade.bin) |

### Ruijie EW-6000GX Pro

| 布局 | 镜像 | 下载 |
| :--- | :--- | :---: |
| 标准 | Initramfs | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-initramfs-kernel.bin) |
| 标准 | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-squashfs-sysupgrade.bin) |
| 原厂布局 | Initramfs | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-stock-initramfs-kernel.bin) |
| 原厂布局 | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-stock-squashfs-sysupgrade.bin) |
| 扩容布局 | Initramfs | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-expand-initramfs-kernel.bin) |
| 扩容布局 | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-expand-squashfs-sysupgrade.bin) |
| U-Boot Mod | Recovery | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-ubootmod-initramfs-recovery.itb) |
| U-Boot Mod | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-ubootmod-squashfs-sysupgrade.itb) |
| U-Boot Mod | Preloader | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-ubootmod-preloader.bin) |
| U-Boot Mod | BL31 + U-Boot | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_ew-6000gx-pro-ubootmod-bl31-uboot.fip) |

### Ruijie RG-X60 New

| 布局 | 镜像 | 下载 |
| :--- | :--- | :---: |
| 标准 | Initramfs | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-initramfs-kernel.bin) |
| 标准 | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-squashfs-sysupgrade.bin) |
| 原厂布局 | Initramfs | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-stock-initramfs-kernel.bin) |
| 原厂布局 | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-stock-squashfs-sysupgrade.bin) |
| 扩容布局 | Initramfs | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-expand-initramfs-kernel.bin) |
| 扩容布局 | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-expand-squashfs-sysupgrade.bin) |
| U-Boot Mod | Recovery | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-ubootmod-initramfs-recovery.itb) |
| U-Boot Mod | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-ubootmod-squashfs-sysupgrade.itb) |
| U-Boot Mod | Preloader | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-ubootmod-preloader.bin) |
| U-Boot Mod | BL31 + U-Boot | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-ruijie_rg-x60-new-ubootmod-bl31-uboot.fip) |

### Super Gateway S20 系列

| 设备 | 镜像 | 下载 |
| :--- | :--- | :---: |
| S20L | Initramfs | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20l-initramfs-kernel.bin) |
| S20L | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20l-squashfs-sysupgrade.bin) |
| S20M | Initramfs | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20m-initramfs-kernel.bin) |
| S20M | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20m-squashfs-sysupgrade.bin) |
| S20P | Initramfs | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20p-initramfs-kernel.bin) |
| S20P | Sysupgrade | [下载](https://github.com/MinimaxFlora/MediaTek_Firmware/releases/download/20261106/zerowrt-mediatek-filogic-supergateway_s20p-squashfs-sysupgrade.bin) |

## 功能特性

以下为项目固件集成方向，具体组件及版本以对应 Release 的实际构建结果为准。

| 模块 | 组件 / 功能 |
| :--- | :--- |
| 界面主题 | Argon、Bootstrap、LuCI |
| 网络代理 | OpenClash、PassWall、Xray |
| DNS 服务 | SmartDNS、ChinaDNS-NG、Dnsmasq-Full |
| 网络加速 | MediaTek TurboACC、HNAT、FullCone NAT、BBR |
| 流量管理 | EQOS-MTK、SQM Cake |
| 网络服务 | UPnP、DDNS、ACME、WireGuard |
| 系统工具 | ttyd、htop、bash、curl、tcpdump |
| 存储支持 | ext4、NTFS3、exFAT、Btrfs、zram |

## 镜像类型说明

| 名称 | 说明 |
| :--- | :--- |
| Initramfs | 临时启动镜像，常用于首次启动、测试或进入临时系统；具体用途请遵循对应设备的刷机教程 |
| Sysupgrade | 系统升级镜像，用于已运行兼容 OpenWrt 系统的设备升级 |
| Standard | 标准分区布局 |
| Stock | 针对原厂分区 / Bootloader 布局制作的镜像 |
| Expand | 扩展可用系统空间的布局 |
| U-Boot Mod | 面向对应修改版 U-Boot 环境的镜像，通常包含 Preloader、FIP、Recovery 和 Sysupgrade 文件 |

**注意：** Standard、Stock、Expand 和 U-Boot Mod 并不是所有设备都支持，也不能互相替代。请严格按照设备型号、硬件版本、当前 Bootloader 和分区布局选择镜像。

## 刷机须知

1. 刷机前确认设备的完整型号及硬件版本，不要只凭外观判断。
2. 只下载与设备型号完全匹配的固件，禁止跨型号刷写。
3. 确认当前 Bootloader 和分区布局，不能将不同布局的镜像混用。
4. 首次刷机前备份原厂固件、分区和重要配置，并确认设备具备对应的恢复方式。
5. 涉及 Preloader、FIP 或 U-Boot 的操作风险较高，务必先阅读对应设备的专用教程。
6. 刷写过程中保持稳定供电，不要断电或强制重启。

## 常见问题

<details>
<summary>所有设备都能使用同一份固件吗？</summary>

不能。每款设备都有独立的设备配置和固件镜像。即使设备使用相同的 MediaTek 芯片，也不代表分区、GPIO、无线校准数据和接口定义相同。请按准确型号下载。
</details>

<details>
<summary>为什么有些设备没有 Stock、Expand 或 U-Boot Mod 镜像？</summary>

不同设备的 Bootloader、分区结构和适配情况不同。Release 中实际提供哪些镜像，就代表当前版本提供哪些构建类型，不应自行套用其他设备的布局。
</details>

<details>
<summary>应该下载 Initramfs 还是 Sysupgrade？</summary>

这取决于设备当前运行的系统和首次刷机方式。Initramfs 通常用于临时启动或恢复环境，Sysupgrade 用于兼容系统升级。请先阅读对应设备的刷机教程，不要仅凭文件名操作。
</details>

## 致谢

- [OpenWrt](https://openwrt.org/)
- [ImmortalWrt](https://github.com/immortalwrt)
- [luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)
- [OpenClash](https://github.com/vernesong/OpenClash)
- [PassWall](https://github.com/xiaorouji/openwrt-passwall)
- [SmartDNS](https://github.com/pymumu/smartdns)
- 以及所有上游开源项目和设备适配贡献者

## 许可证

本项目基于 [GNU General Public License v3.0](LICENSE) 发布。

## 免责声明

本项目固件按「现状」提供，不附带任何明示或暗示的担保。刷机、修改分区、替换 Bootloader 等操作存在风险，可能导致设备损坏、数据丢失或保修失效。请在充分了解风险、确认设备型号并做好备份后操作。因错误选择镜像或不当操作造成的后果由使用者自行承担，并请遵守当地法律法规。

<div align="center">

[返回顶部](#zerowrt--mediatek-filogic-多设备固件) | [English](README_EN.md)

</div>
