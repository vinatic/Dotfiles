<h1 align="center">✨ Dotfiles</h1>

<p align="center">
    <i>These are my configuration files also known as <b>dotfiles</b>.</i>
    <img src="screenshots/cover.png">
</p>

> [!CAUTION]
> This setup is specific for [Hyprland](https://github.com/hyprwm/Hyprland). Dont install it if you don't know what you're doing.
>
> [!CAUTION]
> This is not the original repo!

## 📸 Check it out!
![](screenshots/1.png)
![](screenshots/2.png)
![](screenshots/3.png)
![](screenshots/4.png)
![](screenshots/5.png)
![](screenshots/6.png)

[👉 Reddit Post](https://www.reddit.com/r/unixporn/comments/1hw6ur3/hyprland_are_we_fabricating_yet_wip/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)

> [!WARNING]
> The main branch is experimental, as Axenide is always making changes.
>
> Please refer to the [stable branch](https://github.com/Axenide/Dotfiles/tree/stable) if you want to use it.

## Installation
```bash
git clone https://github.com/Axenide/Dotfiles
cd Dotfiles
bash install.sh
```
This will execute the installation wizard.

> [!CAUTION]
> Does not conaint all packages needed

> [!NOTE]
> [This packages](https://github.com/Axenide/Dotfiles/blob/main/pacman/packages.txt) are needed to fully use the config and will be installed if you choose the option in script:

Also it will install `yay`, but you can skip the installation and use any AUR helper you want and install them manually. 

## Keybindings

### Ax-Shell

| Keys                                         | Action                          |
|---------------------------------------------:|:--------------------------------|
| <kbd>SUPER + D</kbd>                                  | Toggle Dashboard (WIP)                    |
| <kbd>SUPER + A</kbd>                                  | AI Assistant (WIP)              |
| <kbd>SUPER + ,</kbd>                                  | Wallpaper Selector              |
| <kbd>SUPER + SHIFT + B</kbd>                          | Reload bar CSS              |
| <kbd>SUPER + ALT + B</kbd>                            | Restart bar              |
| <kbd>SUPER + CTRL + B</kbd>                           | Toggle bar              |

### Hyprland

| Keys                                         | Action                          |
|---------------------------------------------:|:--------------------------------|
| <kbd>SUPER + Q</kbd>                                  | Close window                    |
| <kbd>SUPER + SHIFT + Esc</kbd>                        | Exit Hyprland                   |
| <kbd>SUPER + R</kbd>                                  | Toggle tiled/floating           |
| <kbd>SUPER + P</kbd>                                  | Toggle pseudo-tiling            |
| <kbd>SUPER + SHIFT + D</kbd>                          | Toggle split                    |
| <kbd>SUPER + F</kbd>                                  | Fullscreen                      |
| <kbd>SUPER + SHIFT + F</kbd>                          | Fake Fullscreen                 |
| <kbd>SUPER + CTRL + F</kbd>                           | Maximize                        |
| <kbd>SUPER + Y</kbd>                                  | Pin window                      |
| <kbd>SUPER + G</kbd>                                  | Center window                   |
| <kbd>SUPER + Arrows or H,J,K,L</kbd>                  | Move window focus               |
| <kbd>SUPER + SHIFT + Arrows or H,J,K,L</kbd>          | Move tiled window               |
| <kbd>SUPER + CTRL + Arrows or H,J,K,L</kbd>        | Resize window                   |
| <kbd>SUPER + ALT + Arrows or H,J,K,L</kbd>            | Move floating window            |
| <kbd>SUPER + [1-9][0]</kbd>                           | Change workspace [1-10]         |
| <kbd>SUPER + SHIFT + [1-9][0]</kbd>                   | Move window to workspace [1-10] |
| <kbd>SUPER + Z</kbd>                                  | Go to previous workspace        |
| <kbd>SUPER + SHIFT + Z</kbd><br><kbd>SUPER + Scroll Down</kbd> | Go to previous active workspace |
| <kbd>SUPER + X</kbd>                                  | Go to next workspace            |
| <kbd>SUPER + SHIFT + X</kbd><br><kbd>SUPER + Scroll Up</kbd>   | Go to next active workspace     |
| <kbd>SUPER + Left Click</kbd>                         | Drag window                     |
| <kbd>SUPER + Right Click</kbd>                        | Drag resize window              |

### Programs

| Keys                                         | Action                          |
|---------------------------------------------:|:--------------------------------|
| <kbd>SUPER + T</kbd>                                  | Open Kitty terminal             |
| <kbd>SUPER + SHIFT + T</kbd>                          | Open floating Kitty terminal    |
| <kbd>SUPER + ALT + T</kbd>                            | Open Kitty with slurp           |
| <kbd>SUPER + E</kbd>                                  | File explorer                   |
| <kbd>SUPER + SHIFT + E</kbd>                          | Floating file explorer          |
| <kbd>SUPER + W</kbd>                                  | Zen Browser                         |
| <kbd>SUPER + SHIFT + W</kbd>                          | Private Zen Browser                 |
| <kbd>SUPER + M</kbd>                                  | Calculator                   |
| <kbd>Print</kbd>                                      | Save and copy screenshot        |
| <kbd>SHIFT + Print</kbd>                              | Copy screenshot                 |
| <kbd>SUPER + SHIFT + S</kbd>                          | Copy area screenshot            |

### Tmux

> [!IMPORTANT]
> **PREFIX** is set to <kbd>CTRL + Space</kbd>

| Keys                | Action                          |
|--------------------:|:--------------------------------|
| <kbd>PREFIX + c</kbd>        | Create window                   |
| <kbd>SHIFT + ALT + H,L</kbd> | Navigate windows                |
| <kbd>PREFIX + [1-9]</kbd>    | Change to window from 1 to 9    |
| <kbd>PREFIX + &</kbd>        | Kill window                     |
| <kbd>PREFIX + /</kbd>        | Vertical split                  |
| <kbd>PREFIX + -</kbd>        | Horizontal split                |
| <kbd>CTRL + H,J,K,L</kbd>    | Navigate panes                  |
| <kbd>PREFIX + { or }</kbd>   | Swap pane position              |
| <kbd>PREFIX + q</kbd>        | Go to pane pressing a number    |
| <kbd>PREFIX + x</kbd>        | Kill pane                       |
| <kbd>PREFIX + s</kbd>        | List sessions                   |
| <kbd>PREFIX + w</kbd>        | List windows                    |
| <kbd>PREFIX + [</kbd>        | Yank mode (copy)                |
| <kbd>v</kbd>                 | Start selection                 |
| <kbd>CTRL + v</kbd>          | Toggle rectangle/line selection |
| <kbd>y</kbd>                 | Yank selection                  |

## 🌐 Browser
I'm currently using [Zen Browser](https://zen-browser.app/) with some custom tweaks. To use my config you need to create a new profile and click on "Select folder". The folder will be located at `~/.zen/Zen/`.

If you just want good [Pywalfox](https://github.com/Frewacom/pywalfox/) support, install the [PywalZen](https://zen-browser.app/themes/d2953516-d239-4ef8-aac5-b238e3dc0360) theme Axenide made!

> [!NOTE]
> Axenide also modified some shortcuts to make them similar to the ones Axenide use in Hyprland.

| Keys                | Action                  |
|--------------------:|:------------------------|
| <kbd>ALT + Z</kbd>  | Previous workspace      |
| <kbd>ALT + X</kbd>  | Next workspace          |
| <kbd>ALT + S</kbd>  | Toggle web panel        |

<p align="center">
<samp>
  <sup>
    <b>
    <i>Please consider giving Axenide a tip. :)</i>
    <br>
    <a href="https://cafecito.app/axenide">☕ Cafecito</a> |
    <a href="https://ko-fi.com/axenide">❤️ Ko-Fi</a> |
    <a href="https://paypal.me/Axenide">💸 PayPal</a>
  </sup>
</samp>
</p>
