
Debian
====================
This directory contains files used to package chaoscoind/chaoscoin-qt
for Debian-based Linux systems. If you compile chaoscoind/chaoscoin-qt yourself, there are some useful files here.

## chaoscoin: URI support ##


chaoscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install chaoscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your chaoscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/chaoscoin128.png` to `/usr/share/pixmaps`

chaoscoin-qt.protocol (KDE)

