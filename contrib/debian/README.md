
Debian
====================
This directory contains files used to package almad/alma-qt
for Debian-based Linux systems. If you compile almad/alma-qt yourself, there are some useful files here.

## pivx: URI support ##


alma-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install alma-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your alma-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

alma-qt.protocol (KDE)

