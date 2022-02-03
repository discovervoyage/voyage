
Debian
====================
This directory contains files used to package voyaged/voyage-qt
for Debian-based Linux systems. If you compile voyaged/voyage-qt yourself, there are some useful files here.

## voyage: URI support ##


voyage-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install voyage-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your voyage-qt binary to `/usr/bin`
and the `../../share/pixmaps/voyage128.png` to `/usr/share/pixmaps`

voyage-qt.protocol (KDE)

