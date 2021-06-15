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
git clone https://aur.archlinux.org/yay-bin.git

cd yay-bin

makepkg -si

# Script Installation
git clone https://github.com/sneccolol2k/archgamingsetup.git && cd archgamingsetup

# Edit The Script and Running It.
Before you run it, Use your text editor of choice, edit archgamingsetup.sh, and comment out the one below that matches your graphics distributor.

now run, sudo chmod +x archgamingsetup.sh

then finally run ./archgamingsetup.sh
