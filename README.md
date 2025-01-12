Realtek bluetooth driver for Linux
===========
### Usage

```
git clone https://github.com/a5a5aa555oo/realtek-bluetooth
cd realtek-bluetooth
make clean modules
sudo make install
sudo make install_fw
```
or
```
git clone https://github.com/a5a5aa555oo/realtek-bluetooth
cd realtek-bluetooth
sudo dkms install $PWD
sudo make install_fw
```
`sudo make install_fw` is optional if your system (/lib/firmware/rtl_bt) has the firmware needed already.

### Note
**ONLY** kernel 5.15 ~ 6.6 are supported.

For kernel 6.6+ users, the built-in bluetooth driver in the kernel should work for you.

Tested with RTL8822BU/RTL8852BE on the following distros and it works fine.

Arch Linux (kernel version: 6.1.123-1-lts61)

Ubuntu 20.04 (kernel version: 5.15.0-124-generic)



