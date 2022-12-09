
Debian
====================
This directory contains files used to package nexnexcoind/nexnexcoin-qt
for Debian-based Linux systems. If you compile nexnexcoind/nexnexcoin-qt yourself, there are some useful files here.

## nexnexcoin: URI support ##


nexnexcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nexnexcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nexnexcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/nexnexcoin128.png` to `/usr/share/pixmaps`

nexnexcoin-qt.protocol (KDE)

