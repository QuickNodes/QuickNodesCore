
Debian
====================
This directory contains files used to package quicknodesd/quicknodes-qt
for Debian-based Linux systems. If you compile quicknodesd/quicknodes-qt yourself, there are some useful files here.

## quicknodes: URI support ##


quicknodes-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install quicknodes-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your quicknodesqt binary to `/usr/bin`
and the `../../share/pixmaps/quicknodes128.png` to `/usr/share/pixmaps`

quicknodes-qt.protocol (KDE)

