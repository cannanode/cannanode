
Debian
====================
This directory contains files used to package CNODEd/CNODE-qt
for Debian-based Linux systems. If you compile CNODEd/CNODE-qt yourself, there are some useful files here.

## CNODE: URI support ##


CNODE-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install CNODE-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your CNODEqt binary to `/usr/bin`
and the `../../share/pixmaps/CNODE128.png` to `/usr/share/pixmaps`

CNODE-qt.protocol (KDE)

