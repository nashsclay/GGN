
Debian
====================
This directory contains files used to package globalgreend/globalgreen-qt
for Debian-based Linux systems. If you compile globalgreend/globalgreen-qt yourself, there are some useful files here.

## globalgreen: URI support ##


globalgreen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install globalgreen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your globalgreenqt binary to `/usr/bin`
and the `../../share/pixmaps/globalgreen128.png` to `/usr/share/pixmaps`

globalgreen-qt.protocol (KDE)

