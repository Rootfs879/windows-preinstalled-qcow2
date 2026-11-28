<div align="center">

# <img src="images/windows.png" width="25"> Windows Pre-Installed QCOW2 Images

**Ready-to-run Windows disk images for QEMU, KVM, libvirt, Proxmox, and virt-manager.**

[![GitHub Release](https://img.shields.io/github/v/release/Rootfs879/windows-preinstalled-qcow2?style=for-the-badge&logo=github&label=Latest%20Release)](https://github.com/Rootfs879/windows-preinstalled-qcow2/releases)
[![Issues](https://img.shields.io/github/issues/Rootfs879/windows-preinstalled-qcow2?style=for-the-badge&logo=github)](https://github.com/Rootfs879/windows-preinstalled-qcow2/issues)
[![Repo Size](https://img.shields.io/github/repo-size/Rootfs879/windows-preinstalled-qcow2?style=for-the-badge&logo=github)](https://github.com/Rootfs879/windows-preinstalled-qcow2)

**[⬇️ Download](https://github.com/Rootfs879/windows-preinstalled-qcow2/releases)** · **[📖 Run with virt-manager](#-run-with-virt-manager)** · **[🐛 Report an Issue](https://github.com/Rootfs879/windows-preinstalled-qcow2/issues)**

</div>

> Skip the setup marathon. Start with a pre-installed Windows or compatible legacy system in your favorite virtualization environment.

## ✨ Features

- 💿 **QCOW2 disk format** for modern virtualization workflows
- 🪟 **Pre-installed Windows releases** across classic, legacy, and specialist editions
- ⚡ **VirtIO drivers included** for improved KVM and libvirt compatibility
- 🧩 **Organized by operating system and edition**
- 🖥️ **Designed for x86 and x86_64 virtual machines**

## 💿 Available Images

| System | Image |
| :--- | :--- |
| Windows | 95 |
| Windows | 2000 |
| Windows | 2000 + Microsoft Office 2000 Premium |
| Windows | XP Service Pack 3 |
| Windows | Fundamental for Legacy PCs (FLP) |
| Windows Server | 2008 Standard Core |
| Windows | Thin PC |
| Windows | 7 (32-bit) |
| ReactOS | 0.4.16 (x86) |
| FreeDOS | 1.4 |
| Windows Embedded | 8.1 Industry Pro |
| Windows | Whistler Build 2542 |
| Windows NT | 4.0 Service Pack 6a |

> Availability and exact builds may vary by release. Check the [releases page](https://github.com/Rootfs879/windows-preinstalled-qcow2/releases) for the latest downloads.

## 📦 Prerequisites

Choose a virtualization platform and ensure your host has enough CPU, memory, and storage:

- **QEMU**
- **KVM**
- **libvirt**
- **Proxmox**
- **virt-manager**

## 🚀 Run with virt-manager

1. Open **virt-manager**.
2. Click **Create a new VM**.
3. Choose **Import existing disk image**.
4. Select the downloaded `.qcow2` file.
5. Set the operating system family to **Windows**.
6. Allocate the CPU, memory, and storage you want to use.
7. Finish the wizard and start the virtual machine.

If virt-manager does not identify the guest correctly, set the operating system type manually during VM creation.

## 🧰 General Usage

```text
1. Download an image from Releases
2. Import it into your virtualization platform
3. Adjust CPU and RAM for the guest
4. Configure networking and storage if needed
5. Boot the virtual machine
```

## 📝 Release Notes

Each release is organized by operating system version and edition. Images may differ in build, bundled drivers, architecture, and configuration details.

- Some images are **x86-specific**.
- Others support **x86_64 environments**.
- VirtIO drivers are included to improve compatibility where supported.

## 🤝 Contributing

Suggestions, bug reports, and improved or new images are welcome.

- [Open an issue](https://github.com/Rootfs879/windows-preinstalled-qcow2/issues)
- [Create a pull request](https://github.com/Rootfs879/windows-preinstalled-qcow2/pulls)

Please include relevant system details, virtualization software, guest configuration, and steps to reproduce any issue.

## ⚠️ License and Redistribution

This repository does not currently declare an explicit license file for the image collection. Please review the individual release files and any included source materials before using or redistributing them.

The workflow files in `.github/workflows/` are licensed under the **MIT License**. This license does not apply to release images or third-party materials.

<div align="center">

**Built for classic software, legacy hardware, and virtualized nostalgia.**

</div> 
