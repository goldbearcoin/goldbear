
Debian
====================
This directory contains files used to package goldbeard/goldbear-qt
for Debian-based Linux systems. If you compile goldbeard/goldbear-qt yourself, there are some useful files here.

## goldbear: URI support ##


goldbear-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install goldbear-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your goldbearqt binary to `/usr/bin`
and the `../../share/pixmaps/goldbear128.png` to `/usr/share/pixmaps`

goldbear-qt.protocol (KDE)

