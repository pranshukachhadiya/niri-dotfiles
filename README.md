## Installation
Installing **Niri** and the pre-requisites.
```
sudo pacman -Syu niri xwayland-satellite xdg-desktop-portal-gnome xdg-desktop-portal-gtk kitty
sudo  pacman -S matugen cava qt6-multimedia-ffmpeg
systemctl --user add-wants niri.service
```
Installing Paru
```
sudo pacman -S --needed base-devel
git clone https://aur.archlinux.org/paru.git
cd paru
makepkg -si
rm -rf ../paru
```

Installing Editors
```
paru -S nvim fresh-editor-bin
```

Installing Dank Material Shell
```
curl -fsSL https://install.danklinux.com | sh
```

## Configuring

Setting up my fish shell.
```
sudo pacman -S fish
curl https://raw.githubusercontent.com/oh-my-fish/oh-my-fish/master/bin/install | fish
paru -S fastfetch
```
```
set -gx VIRTUAL_ENV_DISABLE_PROMPT 1
omf install neolambda
```
