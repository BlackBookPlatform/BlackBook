
Debian
====================
This directory contains files used to package blackbookd/blackbook-qt
for Debian-based Linux systems. If you compile blackbookd/blackbook-qt yourself, there are some useful files here.

## blackbook: URI support ##


blackbook-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blackbook-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blackbookqt binary to `/usr/bin`
and the `../../share/pixmaps/blackbook128.png` to `/usr/share/pixmaps`

blackbook-qt.protocol (KDE)

