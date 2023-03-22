
Installation of Fedora Silverblue

1. [fish](/guides/fish.md)
2. Add flathub repository
```
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
```
3. Install [vscode](https://github.com/owtaylor/toolbox-vscode)
4. Install [Material-Shell](https://github.com/material-shell/material-shell)
5. Tweaks settings
```
// Swap Meta and left Alt key
dconf write /org/gnome/desktop/input-sources/xkb-options "['lv3:ralt_switch', 'altwin:swap_lalt_lwin']"
```
