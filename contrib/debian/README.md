
Debian
====================
This directory contains files used to package pengd/peng-qt
for Debian-based Linux systems. If you compile pengd/peng-qt yourself, there are some useful files here.

## peng: URI support ##


peng-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install peng-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pengqt binary to `/usr/bin`
and the `../../share/pixmaps/peng128.png` to `/usr/share/pixmaps`

peng-qt.protocol (KDE)

