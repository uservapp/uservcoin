
Debian
====================
This directory contains files used to package uservcoind/uservcoin-qt
for Debian-based Linux systems. If you compile uservcoind/uservcoin-qt yourself, there are some useful files here.

## uservcoin: URI support ##


uservcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install uservcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your uservcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/uservcoin128.png` to `/usr/share/pixmaps`

uservcoin-qt.protocol (KDE)

