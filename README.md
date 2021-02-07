# i3mw config

## Required _pacman_ packages
- i3
  - for i3status, i3lock, etc.
- rofi
  - instead of dmenu
- feh
  - for wallpaper and pictures viewing
- archlinux-wallpaper
  - pack of wallpapers with Arch logo
- xfce4-terminal
- [flameshot](https://github.com/flameshot-org/flameshot)
  - for screenshots
- picom
  - for transparency
- ttf-font-awesome
  - icons for status bar
- networkmanager
  - for Wi-Fi
- bluez bluez-utils blueman
  - Bluetooth
- pulseaudio pulseaudio-bluetooth
- lightdm lightdm-gtk-greeter lightdm-gtk-greeter-settings

For _ru_ keyboard layout generate the ru_RU locale:
- /etc/locale.gen
    - Uncomment the _ru_RU.UTF-8 UTF-8_ line
- locale-gen
