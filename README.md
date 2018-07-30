# xf86-video-sisimedia

SiS 771/671 video driver for xorg 1.19

The original source and patches can be found at : https://aur.archlinux.org/packages/xf86-video-sisimedia/


Installation

$ git clone https://github.com/alfarisi/xf86-video-sisimedia.git
$ cd xf86-video-sisimedia
$ ./configure --prefix=/usr --disable-dri
$ make
$ sudo make install
$ sudo cp xorg.conf /etc/X11/xorg.conf


Tested on Debian 9.5 with xorg 1.19