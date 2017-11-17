
Debian
====================
This directory contains files used to package vivoinnovaonexgobyted/vivoinnovaonexgobyte-qt
for Debian-based Linux systems. If you compile vivoinnovaonexgobyted/vivoinnovaonexgobyte-qt yourself, there are some useful files here.

## vivoinnovaonexgobyte: URI support ##


vivoinnovaonexgobyte-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vivoinnovaonexgobyte-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vivoinnovaonexgobyte-qt binary to `/usr/bin`
and the `../../share/pixmaps/vivoinnovaonexgobyte128.png` to `/usr/share/pixmaps`

vivoinnovaonexgobyte-qt.protocol (KDE)

