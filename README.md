# HyprV2-Paru - Metric Version (Celsius instead of Fahrenheit)
An improved Hyprland deployment

collection of dot config files for hyprland with a simple install script for a fresh Arch linux with yay

You can grab the config files and install packages by hand with this command
```
paru -S hyprland-bin kitty waybar-hyprland swww bat                 \ 
swaylock-effects wofi wlogout mako xdg-desktop-portal-hyprland-git  \
swappy grim slurp thunar polkit-gnome python-requests pamixer       \
pavucontrol brightnessctl bluez bluez-utils blueman                 \
network-manager-applet gvfs thunar-archive-plugin file-roller btop  \
pacman-contrib starship ttf-jetbrains-mono-nerd noto-fonts-emoji    \
lxappearance xfce4-settings sddm-git sddm-sugar-candy-git
```

Or you can use the attached script "set-hypr" to install everything for you.

Below is a list of the packages that would be installed

- blueman: Graphical bluetooth manager                                                                              | https://github.com/blueman-project/blueman
- bluez: the bluetooth service                                                                                      | http://www.bluez.org/
- bluez-utils: command line utilities to interact with bluetooth devices                                            | http://www.bluez.org/
- brightnessctl: used to control monitor and keyboard bright level                                                  | https://github.com/Hummer12007/brightnessctl
- btop: Resource monitor that shows usage and stats for processor, memory, disks, network and processes.            | https://github.com/aristocratos/btop
- hyprland: This is the Hyprland compositor                                                                         | https://github.com/hyprwm/Hyprland
- grim: This is a screenshot tool it grabs images from a Wayland compositor                                         | https://sr.ht/~emersion/grim/
- kitty: This is the default terminal                                                                               | https://github.com/kovidgoyal/kitty
- bat: This is a cat clone with syntax highlighting and Git integration for your terminal                           | https://github.com/sharkdp/bat
- starship: allows to customize the shell prompt                                                                    | https://starship.rs/, https://github.com/starship/starship
- waybar-hyprland: This is a fork of waybar with Hyprland workspace support                                         | https://github.com/Alexays/Waybar
- swww: This is used to set an animated desktop background image                                                    | https://github.com/Horus645/swww
- swaylock-effects: This allows for the locking of the desktop its a fork that adds some additional visual effects  | https://github.com/mortie/swaylock-effects
- wofi: This is an application launcher menu                                                                        | https://hg.sr.ht/~scoopta/wofi
- wlogout: This is a logout menu that allows for shutdown, reboot and sleep                                         | https://github.com/ArtsyMacaw/wlogout
- mako: This is a graphical notification daemon                                                                     | https://github.com/emersion/mako
- xdg-desktop-portal-hyprland-git: xdg-desktop-portal backend for hyprland                                          | https://github.com/hyprwm/xdg-desktop-portal-hyprland
- swappy: This is a screenshot editor tool                                                                          | https://github.com/jtheoof/swappy
- slurp: This helps with screenshots, it selects a region in a Wayland compositor                                   | https://github.com/emersion/slurp
- thunar: This is a graphical file manager                                                                          | https://gitlab.xfce.org/xfce/thunar
- polkit-gnome: needed to get superuser access on some graphical application                                        | https://gitlab.gnome.org/GNOME/polkit-gnome, https://archlinux.org/packages/community/x86_64/polkit-gnome/
- python-requests: needed for the weather module script to execute                                                  | https://requests.readthedocs.io/en/latest/
- pamixer: This helps with audio settings such as volume                                                            | https://github.com/cdemoulins/pamixer
- pavucontrol: GUI for managing audio and audio devices                                                             | https://freedesktop.org/software/pulseaudio/pavucontrol/, https://github.com/pulseaudio/pavucontrol
- network-manager-applet: Applet for managing network connection                                                    | https://gitlab.gnome.org/GNOME/network-manager-applet
- gvfs: adds missing functionality to thunar such as automount usb drives                                           | https://gitlab.gnome.org/GNOME/gvfs
- thunar-archive-plugin: Provides a front end for thunar to work with compressed files                              | https://docs.xfce.org/xfce/thunar/archive
- file-roller: Backend set of tools for working with compressed files                                               | https://gitlab.gnome.org/GNOME/file-roller
- pacman-contrib: adds additional tools for pacman. needed for showing system updates in the waybar                 | https://archlinux.org/packages/extra/x86_64/pacman-contrib/
- ttf-jetbrains-mono-nerd: Som nerd fonts for icons and overall look                                                | https://github.com/ryanoasis/nerd-fonts
- noto-fonts-emoji: fonts needed by the weather script in the top bar                                               | https://archlinux.org/packages/extra/any/noto-fonts-emoji/
- lxappearance: used to set GTK theme                                                                               | https://github.com/lxde/lxappearance
- xfce4-settings: set of tools for xfce, needed to set GTK theme                                                    | https://gitlab.xfce.org/xfce/xfce4-settings, https://docs.xfce.org/xfce/xfce4-settings/start
- sddm-git: developement version of SDDM which is a display manager for graphical login                             | https://github.com/sddm/sddm
- sddm-sugar-candy-git: an sddm theme my theme is based on (copy of)                                                | https://aur.archlinux.org/packages/sddm-sugar-candy-git


