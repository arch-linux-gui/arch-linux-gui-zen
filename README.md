# arch-linux-gui-min
Minimal Version of Arch Linux GUI

<h3>ALG = Arch Linux GUI</h3>
GUI = Graphical User Interface<br>
This project aims to help people install Arch Linux with a graphical installer, and provide them with a ready to use Arch Linux environment. The project currently features the KDE Plasma desktop with 3 editions. 
<ul>
  <li>ALG Pure</li>
  <li>ALG Minimal</li>
  <li>ALG (The Flagship)</li>
 </ul>
 <br>
<b>NOTE: You can visually compare ALG Pure & Minimal by viewing the screenshots</b><br>

<h2>ALG MINIMAL</h2>
ALG MINIMAL is my recomendation for people looking forward to a more ready to use Arch Linux version, with <b>basic theming</b> already done. As the name suggests, it indeed is minimal. In fact, the minimal ISO is very simillar to the <b>PURE</b> ISO, except of the following:
<ul>
<li>Dark Theme By Default</li>
<li>Fonts size increased by default in Kate & Konsole</li>
<li>Transprency by default in Konsole</li>
<li>Imporoved Panel</li>
<li>Open terminal option added to dolphin</li>
</ul>
<br>
ALG Minimal contains very little software by default. It comes with only essential software:
<ul>
<li>Dolphin - File Browser</li>
<li>Konsole - Terminal</li>
<li>Kate - Advanced Text Editor</li>
<li>Spectacle - Screenshot Utility</li>
</ul>
All other software can be installed with a simple <code>sudo pacman -S [packgename]</code><br>
The ALG Repository contains 4 other packages: Zoom (for video conferencing), octopi(a GUI software installer), yay (an AUR helper) & timeshoft(a system restore utility).
<br><br>
Just like ALG Pure, <b>ALG MINIMAL</b> is ideal for installing Arch Linux easily on Legacy/UEFI motherboards, and is thoroughly tested for both BISO modes on Intel as well as AMD hardware. The ISO contians only open source drivers that work best with Intel and AMD iGPUs. The ISO also have been thoroughly tested to undergo multi-boot operation with either WIndows or any Linux Distribution.

<h2>Download ALG MINIMAL ISO:</h2>
You can download the ISOs from ALG's Sourceforge Page: https://sourceforge.net/projects/arch-linux-gui/files/archlinux-gui-minimal-2021.03-x86_64.iso/download

<h2>Multibooting ALG with Other Linux Distributions</h2>
Please not that while ALG's grub can detect other distributions, not all distributions's grub might be able to detect ALG. Hence, it is adviced to install ALG at last.

<h2>Dual Booting with Windows</h2>
As the case with many Linux Distributions, you should install ALG after installling Windows on your HDD/SSD.

<h2>Screenshot</h2>
<img src="alg-min-ss.png">
