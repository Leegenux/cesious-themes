# cesious-theme
A theme for awesome window manager. It is designed to integrate nicely with manjaro and adapta gtk theme. However, it is configurable for every need.


#### Installation
Install cesious folder at **/usr/share/awesome/themes/** or anywhere else and use it with `beautiful.init("PATH_TO_CESIOUS_FOLDER/theme.lua")`

- Example usage in **~/.config/awesome/rc.lua** which looks nice with arc gtk theme:

```
beautiful.init("/usr/share/awesome/themes/cesious/theme.lua")
theme.bg_normal = "#2F343F"
theme.bg_focus = "#404552"
theme.font = "Noto Sans Regular 12"
theme.notification_font = "Noto Sans Bold 16"
beautiful.wallpaper = "/usr/share/backgrounds/SOME_WALLPAPER.png"
beautiful.icon_theme="Arc-Maia"
```

#### Optional dependencies:
```
adapta-gtk-theme
noto-fonts
```