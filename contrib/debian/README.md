
Debian
====================
This directory contains files used to package triadd/triad-qt
for Debian-based Linux systems. If you compile triadd/triad-qt yourself, there are some useful files here.

## triad: URI support ##


triad-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install triad-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your triad-qt binary to `/usr/bin`
and the `../../share/pixmaps/triad128.png` to `/usr/share/pixmaps`

triad-qt.protocol (KDE)

