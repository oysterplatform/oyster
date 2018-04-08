
Debian
====================
This directory contains files used to package oysterd/oyster-qt
for Debian-based Linux systems. If you compile oysterd/oyster-qt yourself, there are some useful files here.

## oyster: URI support ##


oyster-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install oyster-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your oysterqt binary to `/usr/bin`
and the `../../share/pixmaps/oyster128.png` to `/usr/share/pixmaps`

oyster-qt.protocol (KDE)

