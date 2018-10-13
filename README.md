# cesious-theme
A theme for awesome window manager. It is designed to integrate nicely with manjaro and matcha gtk theme. However, it is configurable for every need.


#### Installation
Install cesious folder at **/usr/share/awesome/themes/** or anywhere else and use it with `beautiful.init("PATH_TO_CESIOUS_FOLDER/theme.lua")`

- Example usage in **~/.config/awesome/rc.lua**:

```
beautiful.init("/usr/share/awesome/themes/cesious/theme.lua")
beautiful.font = "Noto Sans Regular 12"
beautiful.notification_font = "Noto Sans Bold 16"
beautiful.wallpaper = "/usr/share/backgrounds/SOME_WALLPAPER.png"
beautiful.icon_theme="Papirus-Dark"
```

1. Match with matcha gtk theme (default)
```
beautiful.bg_normal                    = "#141A1B"
beautiful.bg_focus                     = "#222B2E"
beautiful.titlebar_close_button_normal = "PATH_TO_CESIOUS_FOLDER/titlebar/close_normal_arc.png"
beautiful.titlebar_close_button_focus  = "PATH_TO_CESIOUS_FOLDER/titlebar/close_focus_arc.png"
```
2. Match with arc gtk theme:
```
beautiful.bg_normal                    = "#2F343F"
beautiful.bg_focus                     = "#404552"
beautiful.titlebar_close_button_normal = "PATH_TO_CESIOUS_FOLDER/titlebar/close_normal_arc.png"
beautiful.titlebar_close_button_focus  = "PATH_TO_CESIOUS_FOLDER/titlebar/close_focus_arc.png"
```
3. Match with adapta gtk theme:
```
beautiful.bg_normal                    = "#1D1D1D"
beautiful.bg_focus                     = "#080808"
beautiful.titlebar_close_button_normal = "PATH_TO_CESIOUS_FOLDER/titlebar/close_normal_adapta.png"
beautiful.titlebar_close_button_focus  = "PATH_TO_CESIOUS_FOLDER/titlebar/close_focus_adapta.png"
```
