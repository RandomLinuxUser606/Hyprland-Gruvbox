# Hyprland-Gruvbox 🌸
A minimalistic hyprland rice, using the gruvbox color pallete.
![2025-06-04-212600_hyprshot](https://github.com/user-attachments/assets/928c47c5-add8-4d50-8a4c-e3c057fc28a7)

⚠️ This rice was only tested on Arch, I don't guarantee that it will work on other distros.

## Instalation

1: Clone this repository
  git clone https://github.com/RandomLinuxUser606/Hyprland-Gruvbox.git

2: Install all the dependencies and files:
  pacman -S hyprland waybar swaybg rofi kitty nautilus zsh

  Oh my zsh: 
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

  Hyprshot
  yay -S hyprshot

3: Place all files in their respective places.

| File/Configuration          | Location                        |
|-----------------------------|---------------------------------|
| kitty.conf                  | ~/.config/kitty/                |
| hyprland.conf               | ~/.config/hypr/                 |
| waybar (config.jsonc)       | /etc/xdg/waybar/                |
| Wallpaper                   | ~/Pictures/                     |
| GTK Theme                   | ~/.themes/                      |
| Icons                       | ~/.local/share/icons/           |
| Oh My Zsh theme (custom.zsh)| ~/.oh-my-zsh/custom/            |
| fastfetch (config.jsonc)    | ~/.config/fastfetch/config.jsonc |

## Features

- Full Gruvbox theming (GTK, terminal, bar, icons)
- Minimalistic and simple visual
- Made with the keyboard in mind

## Keybindings

### Essential Shortcuts
| **Keybind**          | **Action**                                  |
|----------------------|--------------------------------------------|
| `Super + Q`         | Open terminal (`kitty`)                    |
| `Super + E`         | Open file manager (`nautilus`)             |
| `Super + R`         | Launch Rofi app launcher                   |
| `Super + C`         | Close active window                        |
| `Super + M`         | Exit Hyprland                              |

### 🖥Window Management
| **Keybind**               | **Action**                                  |
|---------------------------|--------------------------------------------|
| `Super + V`              | Toggle floating mode                       |
| `Super + P`              | Toggle pseudotiling                        |
| `Super + J`              | Toggle split layout                        |
| `Super + O`              | Toggle floating for active window          |

### Navigation
| **Keybind**               | **Action**                                  |
|---------------------------|--------------------------------------------|
| `Super + ←/→/↑/↓`        | Move focus between windows                 |
| `Super + Shift + ←/→/↑/↓`| Resize active window (±10px)               |

### Workspaces
| **Keybind**               | **Action**                                  |
|---------------------------|--------------------------------------------|
| `Super + 1-0`            | Switch to workspace 1-10                   |
| `Super + Shift + 1-0`    | Move window to workspace 1-10              |
| `Super + S`              | Toggle special workspace                   |

### Media Controls
| **Keybind**               | **Action**                                  |
|---------------------------|--------------------------------------------|
| `Volume Keys`            | Control audio volume                       |
| `Brightness Keys`        | Adjust screen brightness                   |
| `Media Keys`             | Playback controls (`playerctl`)            |


## Credits

GTK Theme: https://www.gnome-look.org/p/1681313
Icons: https://www.gnome-look.org/p/1961046
Oh my zsh: sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
Oh my zsh theme: https://github.com/sbugzu/gruvbox-zsh
Pallete: https://github.com/morhetz/gruvbox
