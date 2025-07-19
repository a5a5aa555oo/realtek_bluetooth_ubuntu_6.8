## Installation Guide

```
git clone https://github.com/a5a5aa555oo/realtek_bluetooth_ubuntu_6.8
```
```
cd realtek_bluetooth_ubuntu_6.8
```
```
sudo dkms install $PWD
```

## Uninstallation Guide

```
sudo dkms remove btusb/6.15 --all
```
```
sudo rm -rf /usr/src/btusb-6.15
```
```
sudo rm /etc/modprobe.d/blacklist-btusb.conf
```
