# About
These are i3 config files for different distributions. I added programs that are not included in the distribution. It will be required to install majority of the programs to fully utilize my config out of the box. You can use it as a base to customize it yourself to get familiar with i3. 

## Debian Weird Computer
So I have a test computer and I have some weird configuration for i3 where it disbales the laptop monitor and forces the external monitor to be set on workspace 1. My old computer has dead pixels so I accomodate that for external monitor. I uncomment the potentially problematic ones in the config. You can delete them from your config.

## Arch, Debian and Endeavor Config Location:
~/.config/i3/config

## Programs I installed for the Arch Desktop config:
1. terminator 
2. dmenu 
3. leafpad 
4. rofi
5. i3scrot
6. pcmanfm
7. gvfs
8. vivaldi/firefox
9. flameshot
10. redshift
11. nitrogen
12. synapse
13. network-manager-applet 
14. udiskie 
15. polkit-gnome 
16. ckb-next (comment it out if you don't use wired corsair mosue) 
17. xscreensaver
18. pavucontrol
19. pulseaudio
20. unclutter
21. discord

```
sudo pacman -S terminator dmenu leafpad rofi i3scrot pcmanfm gvfs firefox flameshot redshift nitrogen synapse network-manager-applet udiskie polkit-gnome xscreensaver pavucontrol pulseaudio unclutter
```
## Program I installed for the Debian Weird Computer config
1. network-manager-gnome
2. rofi
3. terminator
4. mousepad
5. udiskie
6. nitrogen
7. redshift
9. flameshot
10. firefox/vivaldi
11. dmenu
12. synapse
13. policykit-1-gnome
14. synapse
15. lxqt-powermanagement (for laptop)

```
sudo apt install network-manager-gnome rofi terminator mousepad udiskie nitrogen redshift flameshot firefox dmenu synapse policykit-1-gnome synapse lxqt-powermanagement
```

## Programs I installed for the Endeavor Laptop config:
1. terminator
2. rofi
3. pcmanfm
4. vivaldi
5. flameshot
6. redshift
7. synapse
8. pavucontrol
9. lxqt-powermanagement (for laptop)
10. unclutter

```
sudo pacman -S terminator rofi pacmanfm flameshot redshift synapse pavucontrol lxqt-powermanagement unclutter
```
