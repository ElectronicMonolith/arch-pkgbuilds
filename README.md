# arch-pkgbuilds

Ensure that you have the package group ` base-devel` installed.

> pacman -S base-devel

<br></br>
Recommended to have `namcap` installed.

> pacman -S namcap

<br></br>
Steps to building a package.  
It is recommended to run each build separately rather than `all` in order to check for errors in the build process. 

> bash build.sh <i>[ all | libtorrent-rasterbar | rtorrent | libtorrent | deluge | qbitorrent ]</i>

