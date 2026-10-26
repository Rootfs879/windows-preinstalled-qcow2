# Windows Pre-Installed QCOW2 Images

This repo contains pre-installed Windows QCOW2 images for virtualization.

## Download
Download the image from the [GitHub Releases](https://github.com/Rootfs879/windows-preinstalled-qcow2/releases) page.


## Run in virt-manager
1. Open virt-manager
2. Click "Create a new VM"
3. Choose "Import existing disk image"
4. Select the QCOW2 file
5. Set OS to Windows
6. Finish the setup and start the VM

## Notes
- Different releases may contain different Windows versions
- x86 and x86_64 images are supported
- VirtIO drivers are included for better KVM/libvirt compatibility
