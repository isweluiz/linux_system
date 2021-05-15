# Working with the GRUB 2 Boot Loader

```bash
~]# grubby --default-kernel
/boot/vmlinuz-4.2.0-1.fc23.x86_64

~]# grubby --default-index
0

~]# grubby --set-default /boot/vmlinuz-4.2.0-1.fc23.x86_64


~]$ grubby --info /boot/vmlinuz-4.2.0-1.fc23.x86_64
index=0
kernel=/boot/vmlinuz-4.2.0-1.fc23.x86_64
args="ro rd.lvm.lv=fedora/root rd.lvm.lv=fedora/swap rhgb quiet LANG=en_US.UTF-8"
root=/dev/mapper/fedora-root
initrd=/boot/initramfs-4.2.0-1.fc23.x86_64.img
title=Fedora (4.2.0-1.fc23.x86_64) 23 (Workstation Edition)
```


https://docs.fedoraproject.org/en-US/fedora/rawhide/system-administrators-guide/kernel-module-driver-configuration/Working_with_the_GRUB_2_Boot_Loader/
