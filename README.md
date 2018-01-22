S ROM - Manifest ((WIP))
===========

jOS is an open source Android distrobution based on LineageOS for the Google Pixel 2 and Pixel 2 XL. This repo contains the repo manifest files for downloading the source code. As it stands (January 22, 2018), I'm working on getting core functionality up and running. After, I can begin cherry-picking and implementing my own unique features.

Goals
--------------
* Stay as close to stock Pixel functionality as possible
* Implement unique tweaks to Google's view of the perfect mobile experience
* Stability and Speed which is acheived thanks to a tight Lineage base and ElementalX kernel

To-do
--------------
- [X] Boot
- [X] Wireless drivers
- [X] Gapps
- [X] ElementalX kernel
- [ ] ActiveEdge functionality

^==========="Core functionality"===========^ 
- [ ] Advanced reboot menu (recovery & bootloader)
- [ ] Magisk systemless root preinstalled
- [ ] Custom Gapps install (opengapps cannot be flashed as of yet on pixel 2 devices due to A/B partition scheme)
- [ ] Custom (dark) boot animation
- [ ] Substratum theme engine
- [ ] Navbar tweaks
- [ ] Statusbar tweaks


Getting Started
---------------

To initialize your local repository using the jOS trees, use a command like this:

    repo init -u git://github.com/TheNightmanCodeth/android.git -b los-15.1

Then to sync up:

    repo sync (-j8 to use 8 threads to sync up faster)
