# workspace-hyprbg
randomly changes wallpaper on each workspace.

requires `swaybg` pretty much available with every distro

Arch: `pacman -S swaybg`
Fedora: `dnf install swaybg`
etc

make sure you make the script executable with `exec-once = sh ~/.config/hypr/hyprbgchange.sh` in your hyprland.conf file

after that add the keybindings for your workspace like:

`bind = $mainMod, 1, exec, sh ~/.config/hypr/hyprbgchange.sh
bind = $mainMod, 2, exec, sh ~/.config/hypr/hyprbgchange.sh
bind = $mainMod, 3, exec, sh ~/.config/hypr/hyprbgchange.sh
bind = $mainMod, 4, exec, sh ~/.config/hypr/hyprbgchange.sh
bind = $mainMod, 5, exec, sh ~/.config/hypr/hyprbgchange.sh
bind = $mainMod, 6, exec, sh ~/.config/hypr/hyprbgchange.sh
bind = $mainMod, 7, exec, sh ~/.config/hypr/hyprbgchange.sh
bind = $mainMod, 8, exec, sh ~/.config/hypr/hyprbgchange.sh
bind = $mainMod, 9, exec, sh ~/.config/hypr/hyprbgchange.sh
`
