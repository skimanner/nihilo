
Debian
====================
This directory contains files used to package nihilod/nihilo-qt
for Debian-based Linux systems. If you compile nihilod/nihilo-qt yourself, there are some useful files here.

## nihilo: URI support ##


nihilo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nihilo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nihilo-qt binary to `/usr/bin`
and the `../../share/pixmaps/nihilo128.png` to `/usr/share/pixmaps`

nihilo-qt.protocol (KDE)

