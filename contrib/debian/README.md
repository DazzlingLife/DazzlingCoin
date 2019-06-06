
Debian
====================
This directory contains files used to package dazzlingd/dazzling-qt
for Debian-based Linux systems. If you compile dazzlingd/dazzling-qt yourself, there are some useful files here.

## dazzling: URI support ##


dazzling-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dazzling-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dazzlingqt binary to `/usr/bin`
and the `../../share/pixmaps/dazzling128.png` to `/usr/share/pixmaps`

dazzling-qt.protocol (KDE)

