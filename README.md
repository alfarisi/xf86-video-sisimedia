# xf86-video-sisimedia

SiS 771/671 video driver for xorg 1.19

The original source and patches can be found at : https://aur.archlinux.org/packages/xf86-video-sisimedia/


## Requirements

The packages needed to build this driver in Debian :
* autoconf
* build-essential
* libtool
* pkg-config
* xserver-xorg-dev
* xutils-dev
* x11proto-xf86dga-dev


## Installation

```sh
$ ./configure --prefix=/usr --disable-dri
$ make
$ sudo make install
$ sudo cp xorg.conf /etc/X11/xorg.conf
```

Then restart your X. Good luck!

Tested on Debian 9.5 with xorg 1.19