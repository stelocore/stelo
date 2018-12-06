
Debian
====================
This directory contains files used to package stelod/stelo-qt
for Debian-based Linux systems. If you compile stelod/stelo-qt yourself, there are some useful files here.

## stelo: URI support ##


stelo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stelo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stelo-qt binary to `/usr/bin`
and the `../../share/pixmaps/stelo128.png` to `/usr/share/pixmaps`

stelo-qt.protocol (KDE)

