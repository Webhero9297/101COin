
Debian
====================
This directory contains files used to package 101coind/101coin-qt
for Debian-based Linux systems. If you compile 101coind/101coin-qt yourself, there are some useful files here.

## 101coin: URI support ##


101coin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install 101coin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your 101coinqt binary to `/usr/bin`
and the `../../share/pixmaps/101coin128.png` to `/usr/share/pixmaps`

101coin-qt.protocol (KDE)

