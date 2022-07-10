# Anas Elgarhy's dwm
## My fork from dwm 🍴, with a loat of a beutaful patches 🥰

![dwm screenshot](./screenshots/dwm-0.1.0-6.2.png)
![dwm and alacritty](./screenshots/dwm_bpytop_and_ufetch-0.1.0-6.2.png)

### Applayed patches:
- [alwayscenter](https://dwm.suckless.org/patches/alwayscenter)
- [cool autostart](https://dwm.suckless.org/patches/cool_autostart)
- [fullscreen](https://dwm.suckless.org/patches/fullscreen)
- [gridmode]()
- [keychord](https://dwm.suckless.org/patches/keychord)
- [movestack](https://dwm.suckless.org/patches/movestack)
- [pertag](https://dwm.suckless.org/patches/pertag)
- [systray](https://dwm.suckless.org/patches/systray)
- [sticky](https://dwm.suckless.org/patches/sticky)

### Keys
| Keys                           | Function                                                              |
|--------------------------------|-----------------------------------------------------------------------|
| modkey + shift + d             | Open dmenu (launcher)                                                 |
| modkey + shift + ctrl          | Open rofi launcher (small size)                                       |
| modkey + enter                 | Launche the main terminal (alacritty by default)                      |
| modkey + t -> 1                | Launche the main terminal with tmux                                   |
| modkey + shift + f -> g        | Launche the GUI file manger (dolphin by default)                      |
| modkey + shift + f -> r        | Launche rofi file file browser (small size)                           |
| modkey + w -> g                | Launche google chrome browser                                         |
| modkey + w -> t                | Launche tor browser                                                   |
| modkey + c -> d                | Launche discord                                                       |
| modkey + a -> j                | Launche jetbrains-toolbox                                             |
| modkey + a -> n                | Launche NeoVim in the main terminal                                   |
| modkey + a -> v                | Launche Vim in the main terminal                                      |
| modkey + e                     | Launche rofi emoji selector                                           |
| modkey + f                     | Toggle full screen mode                                               |
| modkey + b                     | Toggle the status bar (hide/show)                                     |
| modkey + j                     | Change the focus to privus window in the stack                        |
| modkey + k                     | Change the focus to the next window in the stack                      |
| modkey + i                     | Change the stack layout to virtecal                                   |
| modkey + d                     | Change the stack layout to horizontal                                 |
| modkey + h                     | Decrease the focus window size                                        |
| modkey + l                     | Increase the focus window size                                        |
| modkey + Tab                   | Toggle between the curent tag and the privus tag                      |
| modkey + shift + j             | Move the focus window down in the stack                               |
| modkey + shift + k             | Move the focus window up in the stack                                 |
| modkey + q -> q                | Quit from the focus window (kill it)                                  |
| modkey + s -> t                | Use the tile layout                                                   |
| modkey + s -> f                | Use the float layout                                                  |
| modkey + s -> m                | Use the monocle layout                                                |
| modkey + s -> g                | Use the grid layout                                                   |
| modkey + s -> space            | Toggle between current layout and tile layout                         |
| modkey + shift + s             | Toggle sticky mode                                                    |
| modkey + alt + f               | Toggle floating window                                                |
| modkey + 0                     | View all tags                                                         |
| modkey + shift + 0             | Mirror the current tag in all tags                                    |
| modkey + comma (,)             | -                                                                     |
| modkey + period (.)            | -                                                                     |
| modkey + shift + comma (,)     | -                                                                     |
| modkey + shift + period (.)    | -                                                                     |
| modkey + (1..9)                | Navigate between tags                                                 |
| PrtSc                          | Take a screenshot using default screenshot tool (spectacle)           |
| modkey + shift + x             | Lock the screen (using betterlockscreen)                              |
| modkey + shift + ctrl + x      | Plasma screen server                                                  |
| modkey + shift + alt + q       | Kill dwm                                                              |

> modkey = win key or super key

### Dependencies (apps)
- `google-chrome-stable` the main web browser
- `alacritty` the main terminal
- `spectacle` the main screenshot tool 
- `dolphin` the GUI file manger
- `rofi`
- `dmenu`
- `libxinerama-dev`\*\*
- `tmux`\*
- `tor-browser`
- `discord`
- `libxft-bgra` for color emojies support
- `jetbrains-toolbox`
- `nvim`\*
- `vim`\*
- `xbacklight` for control in the screen brightness
- `pamixer` for control in the audio level
- `playerctl` for control in the media
- `pactl` for control in the mic
- `betterlockscreen` for lock screen
- `setxkbmap` for switch between keyboard layouts, like (ar, en)
- `slstatus` the status bar
- `picom` compositor , for transparency
- `nitrogen` for set the wallpaper

> \*\*: build dependencie.

### Install
- Maniual:
  1. Run this command to install all avilable dependencies in standerd arch repostory
    ```bash
    sudo pacman -S google-chrome libxft-bgra rofi dmenu tmux tor-browser discord neovim jetbrains-toolbox vim pamixer playerctl betterlockscreen dolphin spectacle alacritty picom nitrogen libxinerama 
    ```
    2. Install yay if you not installed it.
    3. Run this command to install all avilable dependencies in the AUR repostory
      ```bash
      yay -S xkblayout
      ```
      4. Clone this repostory `git clone https://github.com/anas-elgarhy/dwm-anas.git`
      5. Build and install `sudo make clean install`
      6. Enjoy 😉
