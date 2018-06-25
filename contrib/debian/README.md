
Debian
====================
This directory contains files used to package ansd/ans-qt
for Debian-based Linux systems. If you compile ansd/ans-qt yourself, there are some useful files here.

## ans: URI support ##


ans-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ans-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ansqt binary to `/usr/bin`
and the `../../share/pixmaps/ans128.png` to `/usr/share/pixmaps`

ans-qt.protocol (KDE)

