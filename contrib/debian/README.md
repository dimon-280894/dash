
Debian
====================
This directory contains files used to package simplecointestd/simplecointest-qt
for Debian-based Linux systems. If you compile simplecointestd/simplecointest-qt yourself, there are some useful files here.

## simplecointest: URI support ##


simplecointest-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install simplecointest-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your simplecointest-qt binary to `/usr/bin`
and the `../../share/pixmaps/simplecointest128.png` to `/usr/share/pixmaps`

simplecointest-qt.protocol (KDE)

