
Debian
====================
This directory contains files used to package aikid/aiki-qt
for Debian-based Linux systems. If you compile aikid/aiki-qt yourself, there are some useful files here.

## aiki: URI support ##


aiki-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aiki-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aikiqt binary to `/usr/bin`
and the `../../share/pixmaps/aiki128.png` to `/usr/share/pixmaps`

aiki-qt.protocol (KDE)

