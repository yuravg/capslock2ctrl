# capslock2ctrl
Rebind CapsLock to Ctrl

# What for

There are many way to rebind CapsLock key to Ctlr key for Windows
OS([example](https://beebom.com/how-remap-keyboard-windows-10/)), but for VNC connection this
may not work.

I use [Autohotkey](https://autohotkey.com) script
```ahk
; Caps Lock acts as Control
CapsLock::Ctrl
return
```
or just run
[capslock2ctrl.exe](https://github.com/yuravg/capslock2ctrl/raw/master/autohotkey/capslock2ctrl.exe)
(Ahk2exe Autohotkey Script to EXE converter output file)
