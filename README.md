# hyprland Installation on Arch Linux

## Overview

Install script for the Window Manager called hyprland. Use the script called **install-hyprland**.

Check [My guide to Arch Installation](https://github.com/jbarozet/guide-archlinux) to install Arch Linux.


## If Gnome is also used

If you use Gnome, you have to copy Hyperland Desktop entry to add an Hyperland menu entry in the logging manager (GDM):

`sudo cp hyprland.desktop /usr/share/wayland-sessions`


## Packages

- hyprland-bin: This is the Hyprland compositor
- xdg-desktop-portal-hyprland-git: xdg-desktop-portal backend for hyprland
- waybar-hyprland: This is a fork of waybar with Hyprland workspace support
- swaybg: This is used to set a desktop background image
- swaylock-effects: This allows for the locking of the desktop its a fork that adds some editional visual effects
- wofi: This is an application launcher menu
- wlogout: This is a logout menu that allows for shutdown, reboot and sleep
- mako: This is a graphical notification daemon
- kitty: This is the default terminal
- thunar: This is a graphical file manager
- ttf-jetbrains-mono-nerd: Som nerd fonts for icons and overall look
- noto-fonts-emoji: fonts needed by the weather script in the top bar
- polkit-gnome: needed to get superuser access on some graphical applications
- python-requests: needed for the weather module script to execute
- swappy: This is a screenshot editor tool
- grim: This is a screenshot tool it grabs images from a Wayland compositor
- slurp: This helps with screenshots, it selects a region in a Wayland compositor
- pamixer: This helps with audio settings such as volume
- brightnessctl: used to control monitor bright level
- gvfs: adds missing functionality to thunar such as automount usb drives
- bluez: the bluetooth service
- bluez-utils: command line utilities to interact with bluetooth devices
- lxappearance: used to set GTK theme
- xfce4-settings: set of tools for xfce, needed to set GTK theme
- dracula-gtk-theme: the Dracula theme, it fits the overall look and feel
- dracula-icons-git" set of icons to go with the Dracula theme


