
Debian
====================
This directory contains files used to package triskelpremiumd/triskelpremium-qt
for Debian-based Linux systems. If you compile triskelpremiumd/triskelpremium-qt yourself, there are some useful files here.

## triskelpremium: URI support ##


triskelpremium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install triskelpremium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your triskelpremiumqt binary to `/usr/bin`
and the `../../share/pixmaps/triskelpremium128.png` to `/usr/share/pixmaps`

triskelpremium-qt.protocol (KDE)

