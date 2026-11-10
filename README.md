# Windows Pre-Installed QCOW2 Images

[![GitHub Release](https://img.shields.io/github/v/release/Rootfs879/windows-preinstalled-qcow2)](https://github.com/Rootfs879/windows-preinstalled-qcow2/releases)
[![Issues](https://img.shields.io/github/issues/Rootfs879/windows-preinstalled-qcow2)](https://github.com/Rootfs879/windows-preinstalled-qcow2/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/Rootfs879/windows-preinstalled-qcow2)](https://github.com/Rootfs879/windows-preinstalled-qcow2/pulls)
[![Repo Size](https://img.shields.io/github/repo-size/Rootfs879/windows-preinstalled-qcow2)](https://github.com/Rootfs879/windows-preinstalled-qcow2)

A collection of pre-installed Windows QCOW2 disk images for virtualization environments such as QEMU, KVM, libvirt, Proxmox, and virt-manager.

These images are intended to make it easy to spin up Windows-based virtual machines without going through a full installation process from scratch.

## Features

- Pre-installed Windows operating systems
- QCOW2 disk format
- Compatible with x86 and x86_64 virtual machines
- VirtIO drivers included for better KVM/libvirt compatibility
- Organized by Windows release and edition

## Available Images

The project includes a range of legacy and specialist Windows images, including:

- Windows 95
- Windows 2000
- Windows 2000 with Microsoft Office 2000 Premium
- Windows XP (Service Pack 3)
- Windows Fundamental for Legacy PCs (FLP)
- Windows Server 2008 (Standard Core)
- Windows Thin PC
- Windows 7 (32-bit)
- ReactOS 0.4.16 (x86)
- FreeDOS 1.4

## Download

Visit the Releases page to download the image you need:

https://github.com/Rootfs879/windows-preinstalled-qcow2/releases

## Prerequisites

To run these images, you will typically need a virtualization platform such as:

- QEMU
- KVM
- libvirt
- Proxmox
- virt-manager

You should also have enough free disk space and a host system that can allocate the required CPU and memory for the guest VM.

## Run in virt-manager

1. Open virt-manager.
2. Click "Create a new VM".
3. Choose "Import existing disk image".
4. Select the downloaded QCOW2 file.
5. Set the operating system to Windows.
6. Adjust CPU, memory, and storage settings if needed.
7. Finish the setup and start the VM.

If virt-manager does not detect the guest correctly, you can set the OS type manually during VM creation.

## Release Notes

This repository organizes releases by operating system version and edition. Different images may include different builds, drivers, and configuration details depending on the target system.

## Issues

If you find a problem or have a question, open an issue here:

https://github.com/Rootfs879/windows-preinstalled-qcow2/issues

## Pull Requests

If you want to contribute improvements or add new images, open a pull request here:

https://github.com/Rootfs879/windows-preinstalled-qcow2/pulls

## Notes

- Different releases may contain different Windows versions and editions.
- Some images are x86-specific while others support x86_64 environments.
- VirtIO drivers are included for improved compatibility with KVM and libvirt.
- These are legacy and specialized images intended for virtualization use cases.

## License

This repository does not currently declare an explicit license file. Please review the individual release files and source materials before using them in other projects or redistributing them.
