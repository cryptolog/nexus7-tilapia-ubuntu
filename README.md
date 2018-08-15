## Ubuntu for Nexus 7 (tilapia)

A modification of Ubuntu 12.10 installation for Nexus 7 (the original version can be found here: https://wiki.ubuntu.com/Nexus7/Installation).

Main changes are:

* Recovery kernel with special initramfs. Used to reinstall kernel and format /data partition if needed.
* Installation rootfs located on /system partition. On first boot it will be unpacked to /data partition.
* Fixed repository URLs.

![Screenshot](screenshot.gif)
