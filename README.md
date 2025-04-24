# fonts
My Fonts For Daily Use


# Install fonts on the system

clone the repo

```bash
git clone https://github.com/ezzobir/fonts 

doas mkdir -p /usr/local/share/fonts

z fonts

doas rsync -av --exclude='README.md' ./ /usr/local/share/fonts/

```

# Update Fonts and Config

```bash
doas fc-cache -fv
```

# Reboot

```bash
reboot
```

# Firefox

Change `Sans-serif Arabic font` to `Noto Sans Arabic` or `Noto Sans Arabic UI`

# FlatPak apps

copy the `~/.config/fontconfig/fonts.conf` file to `~/.var/app/<APP-FOLDER>/config/fontconfig/`
