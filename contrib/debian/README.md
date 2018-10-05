
Debian
====================
This directory contains files used to package dropcoind/dropcoin-qt
for Debian-based Linux systems. If you compile dropcoind/dropcoin-qt yourself, there are some useful files here.

## dropcoin: URI support ##


dropcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dropcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dropcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/dropcoin128.png` to `/usr/share/pixmaps`

dropcoin-qt.protocol (KDE)

