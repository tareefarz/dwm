
# Tareef's DWM Build

tareefs dwm build which **sucksless**

### ⚠️⚠️ DEPENDENCIES ⚠️⚠️⚠️
* picom: for compositing (transparency stuff if you don't know what compositing means (not full meaning) )
* dmenu: suckless' menu for executing code
* nitrogen: wallpaper (optional)
* kitty: terminal (optional)
* firefox: browser (optional)

### To install this build of dwm, paste this code into a terminal.

```
cd <path-to-tardwm>
sudo make install
```

### To uninstall this build of dwm, paste this code into a terminal.

```
cd <path-to-tardwm>
sudo make clean uninstall
cd ..
sudo rm -r tardwm
```

### Remember to paste this into your `.xinitrc` file.

```
setxkbmap us &

xset r rate 350 50 &

xset b on &

xset s 1800 &

picom -f &

# nitrogen --restore &  wallpaper

# slstatus & # statusbar

exec dwm
```
