# My i3wm config
 ### this is some my config backup.
 ![](https://www.hualigs.cn/image/6084d6579173b.jpg)

 ## i3wm (gaps)
- termite, for terminal emulator (Mod+Enter)
- feh, for wallpaper (random the image file in `~/.wallpaper`)
- rofi, for app launcher (Mod+d)
- ranger, console file manager(Alt+f)
- polybar
- flameshot, for screent shot(Alt+a)

---

 ## install
 ### 1. Installation of required software

 ```bash
 sudo pacman -S i3-gaps termite picom feh i3lock polybar rofi ranger
 ```

### 2. Install

```bash
git clone https://github.com/qlAD/qlad-i3wm.git
```

```bash
./install.sh
```

### 3. Install fonts

#### My Font
I use the `Source Code Pro` font and `nerd-fonts-source-code-pro`.

#### About Noto
Just install `noto-fonts` (not `-all`). It's already bloated. Check `/usr/share/fonts/noto`

#### Emoji
```bash
yay -S otf-font-awesome
yay -S ttf-material-icons 
```

#### Chinese
```bash
pacman -S adobe-source-han-sans-cn-fonts
pacman -S adobe-source-han-sans-tw-fonts
pacman -S adobe-source-han-sans-jp-fonts
```

---

### 4. Add after ".xinitrc" file

```ini
exec i3
```



# Come From
#### [chaichunyang](https://github.com/chaichunyang/)
#### [theniceboy](https://github.com/theniceboy)

