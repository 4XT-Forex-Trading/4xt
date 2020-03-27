
Debian
====================
This directory contains files used to package forextradingd/forextrading-qt
for Debian-based Linux systems. If you compile forextradingd/forextrading-qt yourself, there are some useful files here.

## forextrading: URI support ##


forextrading-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install forextrading-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your forextradingqt binary to `/usr/bin`
and the `../../share/pixmaps/forextrading128.png` to `/usr/share/pixmaps`

forextrading-qt.protocol (KDE)

