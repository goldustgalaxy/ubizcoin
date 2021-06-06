
Debian
====================
This directory contains files used to package ubizcoind/ubizcoin-qt
for Debian-based Linux systems. If you compile ubizcoind/ubizcoin-qt yourself, there are some useful files here.

## ubizcoin: URI support ##


ubizcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ubizcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ubizcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ubizcoin128.png` to `/usr/share/pixmaps`

ubizcoin-qt.protocol (KDE)

