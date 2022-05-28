
Debian
====================
This directory contains files used to package qwcd/qwc-qt
for Debian-based Linux systems. If you compile qwcd/qwc-qt yourself, there are some useful files here.

## qwc: URI support ##


qwc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install qwc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your qwc-qt binary to `/usr/bin`
and the `../../share/pixmaps/qwc128.png` to `/usr/share/pixmaps`

qwc-qt.protocol (KDE)

