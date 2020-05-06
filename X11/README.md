# Turn CapsLock into Control for Xorg

Create
```bash
xmodmap -pke > ~/.Xmodmap
```
Test
```bash
xmodmap ~/.Xmodmap
```
Add to ~/.Xmodmap:
```bash
clear lock
clear control
keycode 66 = Control_L
add control = Control_L Control_R
```

https://wiki.archlinux.org/index.php/Xmodmap
