
Debian
====================
This directory contains files used to package versusd/versus-qt
for Debian-based Linux systems. If you compile versusd/versus-qt yourself, there are some useful files here.

## versus: URI support ##


versus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install versus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your versus-qt binary to `/usr/bin`
and the `../../share/pixmaps/versus128.png` to `/usr/share/pixmaps`

versus-qt.protocol (KDE)

