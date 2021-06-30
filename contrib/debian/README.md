
Debian
====================
This directory contains files used to package eternd/etern-qt
for Debian-based Linux systems. If you compile eternd/etern-qt yourself, there are some useful files here.

## etern: URI support ##


etern-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install etern-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eternqt binary to `/usr/bin`
and the `../../share/pixmaps/etern128.png` to `/usr/share/pixmaps`

etern-qt.protocol (KDE)

