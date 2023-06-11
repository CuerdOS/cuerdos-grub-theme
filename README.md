# CuerdOS Grub Theme
Grub theme for CuerdOS
The official Grub theme for CuerdOS, based on the Xenlism Grub Theme [https://github.com/xenlism/Grub-themes]
The reason for this fork has been to build on an already well-built theme to modify it so that it has the visual identity of CuerdOS.

### Installation guide for Debian based distros:

```
sudo nano /etc/default/grub
```
Once inside the file, you must change the following value:
```
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash"
```
And paste this at the bottom (don't forget to leave the last line empty):
```
GRUB_THEME="/boot/grub/themes/cuerdos-grub/theme.txt"

```
