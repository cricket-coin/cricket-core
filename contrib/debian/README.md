
Debian
====================
This directory contains files used to package crkd/crk-qt
for Debian-based Linux systems. If you compile crkd/crk-qt yourself, there are some useful files here.

## crk: URI support ##


crk-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install crk-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your crk-qt binary to `/usr/bin`
and the `../../share/pixmaps/crk128.png` to `/usr/share/pixmaps`

crk-qt.protocol (KDE)

