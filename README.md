# Kazari's dotfiles

## Basic info
- **Window manager**: <code> [bspwm](https://github.com/baskerville/bspwm) </code> <br>
- **Compositor**: <code> [picom](https://github.com/yshui/picom) </code> <br>
- **Terminal**: <code> [alacritty](https://github.com/alacritty/alacritty) </code> <br>
- **Shell**: <code> [fish](https://github.com/fish-shell/fish-shell) </code> <br>
- **Panel**: <code> [polybar](https://github.com/polybar/polybar) </code> <br>
- **App launcher**: <code> [rofi](https://github.com/davatorium/rofi) </code> <br>
- **File browser**: <code> [thunar](https://github.com/xfce-mirror/thunar) </code> <br>

## Apps
- **Browser**: <code> Brave </code> <br>
- **Office**: <code> Libre office </code> <br>
- **Video player**: <code> mpv, VLC </code> <br>
- **Music player**: <code> Spotify </code> <br>
- **Image editor**: <code> Gimp, Inkscape </code> <br>
- **Video editor**: <code> DaVinci Resolve </code> <br>
- **Text editor**: <code> Vim, Neovim </code> <br>
- **Code editor**: <code> Visual Studio Code </code> <br>
- **Notepad**: <code> Notepadqq </code> <br>
- **3D graphics**: <code> Blender </code> <br>
- **PDF reader**: <code> Zathura </code> <br>
- **Study**: <code> Anki, Obsidian </code> <br>
- **Communicator**: <code> Discord </code> <br>
- **Password manager**: <code> Bitwarden </code> <br>

## Theme
- **Palette**: <code> [Catppuccin Mocha](https://github.com/catppuccin) </code> <br>
- **Icons**: <code> [Papirus Dark + Catppuccin](https://github.com/catppuccin/papirus-folders) </code> <br>
- **Cursor**: <code> [Catpuccin cursor lavender](https://github.com/catppuccin/cursors) </code> <br>
- **Spotify**: <code> [Spicetify + Catppuccin](https://github.com/catppuccin/spicetify) </code> <br>
- **Discord**: <code> [BetterDiscord + Catppuccin](https://github.com/catppuccin/discord) </code> <br>
- **Fonts**:
    - **System font**: <code> Cantarella </code> 
    - **Console font**: <code> [Cascadia Code](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/CascadiaCode) </code>

## To-do
- [ ] Configure polybar
- [ ] Tidy up .config files
- [ ] Customize Spotify
- [ ] Customize Discord
- [ ] Customize Anki
- [ ] Customize terminal

## Sxhkd hotkeys

### Common keybinds
| Keybind | Action |
|---|---|
| super + enter | Terminal |
| super + r | App launcher |
| super + b | Browser |
| super + f | File manager | 
| super + t | Text editor |


### Window management 
| Keybind | Action |
| --- | --- |
| super + h/j/k/l | Focus left/down/up/right |
| super + arrows | Focus left/down/up/right |
| super + shift + h/j/k/l | Swap windows |
| super + shift + arrows | Swap windows |
| super + alt + 1-5 | Move focused window to given workspace |
| super + q | Quit window |
| super + m | Maximise window |
| super + s | Toggle tiled mode |
| super + t | Toggle tiled state |
| super + s | Toggle between floating and previous state |
| super + z | Toggle between pseudo tiled and previous state |


### Workspace management
| Keybind | Action |
| --- | --- |
| super + 1-5 | Focus workspace 1-5 |
| alt + tab | Focus last used workspace |
| super + tab | Focus next workspace in order |
| super + alt + tab | Focus previous workspace in order |


### Other
| Keybind | Action |
| --- | --- |
| super + shift + s | Selected area screenshot |
| super + f | Full screenshot |
| super + escape | Reload sxhkd |
| super + shift + r | Reload bspwm |
| super + shift + q | Quit bspwm |
| fn + f1 | Mute |
| fn + f3 | Volume up |
| fn + f2 | Volume down |
| fn + f12 | Brightness up |
| fn + f12 | Brightness down |
