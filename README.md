
```
/etc/default/grub

GRUB_DEFAULT=0
GRUB_TIMEOUT_STYLE=menu
GRUB_TIMEOUT=60
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash"
GRUB_CMDLINE_LINUX=""
GRUB_THEME="/boot/grub/themes/mobpsycho-grub/theme.txt"
GRUB_GFXMODE=1920x1200
GRUB_GFXPAYLOAD_LINUX=keep

```
```
sudo update-grub
```
