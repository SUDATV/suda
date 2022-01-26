
Debian
====================
This directory contains files used to package sudad/suda-qt
for Debian-based Linux systems. If you compile sudad/suda-qt yourself, there are some useful files here.

## suda: URI support ##


suda-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install suda-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your suda-qt binary to `/usr/bin`
and the `../../share/pixmaps/suda128.png` to `/usr/share/pixmaps`

suda-qt.protocol (KDE)

