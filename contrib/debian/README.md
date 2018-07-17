
Debian
====================
This directory contains files used to package penguind/penguin-qt
for Debian-based Linux systems. If you compile penguind/penguin-qt yourself, there are some useful files here.

## penguin: URI support ##


penguin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install penguin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your penguinqt binary to `/usr/bin`
and the `../../share/pixmaps/penguin128.png` to `/usr/share/pixmaps`

penguin-qt.protocol (KDE)

