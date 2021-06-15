# Arch Gaming Setup
This shell script is to setup Gaming on Arch Linux (Based on the Lutris dependencies and drivers page)

https://github.com/lutris/docs/blob/master/InstallingDrivers.md  

https://github.com/lutris/docs/blob/master/WineDependencies.md
# Enable Multilib if you haven't
Comment out this at /etc/pacman.conf
<pre style="margin-bottom: 0; border-bottom:none; padding-bottom:0.8em;">
[multilib]
Include = /etc/pacman.d/mirrorlist</pre>

# Install Git if you haven't (Required)
sudo pacman -S git

# Install Yay (Required)
https://aur.archlinux.org/yay-bin.git

cd yay-bin

makepkg -si

# Script Installation
git clone https://github.com/sneccolol2k/archgamingsetup.git

cd archgamingsetup

# Edit The Script and Running It.
Use your text editor of choice, and comment out the one that fits your graphics card distributor.

then, sudo chmod +x gamingsetup.sh

now finally run ./gamingsetup.sh
