NAS-NS2MAX-mod
==============

A set of mods to completely replace LACIE Network Space Max v2 NAS box firmware.

Recommended read order:

- Get SERIAL ACCESS: http://lacie.nas-central.org/wiki/Serial_port_(Network_space_2)

- cross-compile/codesourcery-lite.txt
	- Prepare Cross Compile for ARM and U-Boot Kernel build

- uboot/custom_u-boot.txt
	- Compile new U-Boot and bootloader options

- rootfs/mdadm.txt
	- Compile MDADM statically for RAID-1 setups. This will use CROSSTOOL-NG

- rootfs/initramfs.txt
	- Compile Initramfs instructions

- rootfs/rootfs.txt
	- Build Debian 7.0 rootfs

- kernel/kernel.txt
	- Compile Kernel instructions

- install/install-on-usb.txt
	- install rootFS on USB stick
	
- install/install-on-hdd_mdadm.txt
	- install from USB to new RAID-1 internal disks

- samba/smb.conf
	- Special SAMBA configuration to optimize performance on this device


- Go to https://github.com/davidedg/NAS-mod-config for further customizations

