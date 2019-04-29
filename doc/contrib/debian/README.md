
Debian
====================
This directory contains files used to package corgicoind/corgicoin-qt
for Debian-based Linux systems. If you compile corgicoind/corgicoin-qt yourself, there are some useful files here.

## corgicoin: URI support ##


corgicoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install corgicoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your corgicoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

corgicoin-qt.protocol (KDE)

