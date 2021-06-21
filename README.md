# Garuda-Install

## Post install

Update key rings

> yes | sudo pacman -Sy archlinux-keyring && yes | sudo pacman -Sy chaotic-keyring

Synchronize the package manager with the **refresh** and **system upgrade** options switched on.

> sudo pacman -Syu

