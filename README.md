# ArchLinuxGUI
ArchLinux GUI
33. Install the X

sudo pacman -Syu
sudo pacman -S xorg xorg-server

34. Install Gnome

sudo pacman -S gnome

35. Install GDM

sudo pacman -S gdm

pacman -Qs gdm

36. sudo systemctl enable --now gdm.service

sudo systemctl status gdm.service

sudo pacman -S firefox vlc leafpad

sudo reboot
