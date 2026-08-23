## Installation
Installing **Niri** and the pre-requisites.
```
sudo pacman -Syu niri xwayland-satellite xdg-desktop-portal-gnome xdg-desktop-portal-gtk alacritty
sudo  pacman -S matugen cava qt6-multimedia-ffmpeg fresh 
systemctl --user add-wants niri.service

Installing Dank Material Shell
curl -fsSL https://install.danklinux.com | sh
```

## Configuring

Setting up my fish shell.
```
sudo pacman -S fish
curl https://raw.githubusercontent.com/oh-my-fish/oh-my-fish/master/bin/install | fish

set -gx VIRTUAL_ENV_DISABLE_PROMPT 1
omf install neolambda
```
