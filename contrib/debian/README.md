
Debian
====================
This directory contains files used to package ftcoind/ftcoin-qt
for Debian-based Linux systems. If you compile ftcoind/ftcoin-qt yourself, there are some useful files here.

## ftcoin: URI support ##


ftcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ftcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ftcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/ftcoin128.png` to `/usr/share/pixmaps`

ftcoin-qt.protocol (KDE)

