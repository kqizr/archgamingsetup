# Arch Gaming Setup
This shell script is to setup Gaming on Arch Linux (Based on the Lutris dependencies and drivers page)

https://github.com/lutris/docs/blob/master/InstallingDrivers.md  

https://github.com/lutris/docs/blob/master/WineDependencies.md
# Enable Multilib if you haven't
Comment out this
<pre style="margin-bottom: 0; border-bottom:none; padding-bottom:0.8em;">/etc/pacman.conf
--------------------------------------------------------------------------------------
[multilib]
Include = /etc/pacman.d/mirrorlist</pre>

# Install Git if you haven't (Required)
sudo pacman -S git

# Install Yay (Required)
https://aur.archlinux.org/yay-bin.git
cd yay-bin
makepkg -si

# Script Installation
git clone https://github.com
