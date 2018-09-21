
Debian
====================
This directory contains files used to package uservd/userv-qt
for Debian-based Linux systems. If you compile uservd/userv-qt yourself, there are some useful files here.

## userv: URI support ##


userv-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install userv-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your uservqt binary to `/usr/bin`
and the `../../share/pixmaps/userv128.png` to `/usr/share/pixmaps`

userv-qt.protocol (KDE)

