
Debian
====================
This directory contains files used to package xvicd/xvic-qt
for Debian-based Linux systems. If you compile xvicd/xvic-qt yourself, there are some useful files here.

## xvic: URI support ##


xvic-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xvic-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xvicqt binary to `/usr/bin`
and the `../../share/pixmaps/xvic128.png` to `/usr/share/pixmaps`

xvic-qt.protocol (KDE)

