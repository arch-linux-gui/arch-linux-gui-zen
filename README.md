# ALG Experimental Edition

Welcome to Arch Linux GUI's Experimental Edition Section. Here, you will find editions of Arch Linux that come which components which vary with Vanilla Arch Linux.

###### RELEASE CYCLE: _Whenever ready, and not on the first of every month. Also, not with the mainline ISOs._
---
###  Arch Linux GUI Zen Edition
###### Checksum: `83b9ebf37d288dab373338168e4393a59727d2a28eb29de2c87e5cbefed33434`
`NOTE: Internet Connection is required to install this edition`

The ALG Zen edition differs from the Vanilla editions due to the inclusion of the following core components:
- The Linux Zen Kernel (Increased Responsiveness)
- Zsh as default shell
- btrFS as default File System (Automatic Partition Subvolumes: `/, /home, /var/cache, /var/log`)
- Z standard compression for ISO image (Lightning fast installation)
- Chaotic AUR Repository (Install AUR packages from terminal)

![](https://raw.githubusercontent.com/arch-linux-gui/artwork/master/desktop-screenshots/desktop-ss/experimental/zen-fetch.png)

![](https://raw.githubusercontent.com/arch-linux-gui/artwork/master/desktop-screenshots/desktop-ss/experimental/btrfs-duf.png)

## Features
- KDE Plasma 5 on LiveCD (25th Anniversary Edition)
- Install Stock Desktop of Choice (with option for i3WM as well)
- Install Applications of Choice (Browser, Multimedia, Developement, etc)
- Network info copied over to future system (auth after reboot)
- Network Managed for Xfce, MATE, LxQt (applet)
- NVIDIA Driver Support
- Multilib Enabled
- PAMAC Software Center
- SDDM default with Arch Linux Wallpaper
- Tap-to-click on Laptop touchpads

![](https://raw.githubusercontent.com/arch-linux-gui/artwork/master/desktop-screenshots/desktop-ss/experimental/choose-desktop.png)

![](https://raw.githubusercontent.com/arch-linux-gui/artwork/master/desktop-screenshots/desktop-ss/experimental/software.png)

## Installation
Press Window's key to launch application menu and search for **installer** or **Arch Linux**, and while `Install Arch Linux` is selected, press enter to launch the installer.

![](https://raw.githubusercontent.com/arch-linux-gui/artwork/master/desktop-screenshots/desktop-ss/experimental/install.png)
The installer will launch and you should get something like this:
![](https://raw.githubusercontent.com/arch-linux-gui/artwork/master/desktop-screenshots/desktop-ss/experimental/installer.png)

For partitioning with above mentioned subvolume scheme, select **Erase Disk**
![](https://raw.githubusercontent.com/arch-linux-gui/artwork/master/desktop-screenshots/desktop-ss/experimental/btrfs.png)

`IMPORTANT`: You should select **Erase Disk** only if you are installing to one HDD/SSD, and wish to install Arch Linux on the entire disk. In all other cases, including implementation of your own subvolume scheme, **Manual Partioning** should be used.
