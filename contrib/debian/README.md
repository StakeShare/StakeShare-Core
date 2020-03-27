
Debian
====================
This directory contains files used to package stakeshared/stakeshare-qt
for Debian-based Linux systems. If you compile stakeshared/stakeshare-qt yourself, there are some useful files here.

## stakeshare: URI support ##


stakeshare-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stakeshare-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stakeshareqt binary to `/usr/bin`
and the `../../share/pixmaps/stakeshare128.png` to `/usr/share/pixmaps`

stakeshare-qt.protocol (KDE)

