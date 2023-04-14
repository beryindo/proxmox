# proxmox
Proxmox Server Board S1200BTS
```
chmod 1777 /tmp
apt update

Xorg -configure
cp /xorg.conf.new /etc/X11/xorg.conf
vi /etc/X11/xorg.conf
Change Driver from "modeset" to "fbdev"

xinit
```
