
Debian
====================
This directory contains files used to package nocnocd/nocnoc-qt
for Debian-based Linux systems. If you compile nocnocd/nocnoc-qt yourself, there are some useful files here.

## nocnoc: URI support ##


nocnoc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nocnoc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nocnocqt binary to `/usr/bin`
and the `../../share/pixmaps/nocnoc128.png` to `/usr/share/pixmaps`

nocnoc-qt.protocol (KDE)

