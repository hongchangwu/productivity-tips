# Linux

## Install X11 in RHEL

```
yum groupinstall "X Window System" "Desktop" "Fonts" "General Purpose Desktop"
```

For GNOME

```
yum groupinstall "X Window System" "GNOME Desktop Environment"
```

For KDE

```
yum groupinstall "X Window System" KDE
```

For XFCE

```
yum groupinstall "X Window System" XFCE
```

## Escape quotes in shell

```
echo $'\'single quote phrase\' "double quote phrase"'
```
