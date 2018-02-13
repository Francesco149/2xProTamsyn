ProFont-11 2x upscaled and with a couple extra glyphs taken
and adjusted from Tamsyn

![](https://i.imgur.com/BrIzSE7.png)

I use this font for terminals and programming. you can find it packaged for
gentoo in my [personal overlay](https://github.com/Francesco149/loli-overlay)

# installing
```
mkdir -p /usr/share/fonts/X11/misc
bdftopcf 2xProTamsyn_r400-11.bdf \
| gzip \
| sudo tee /usr/share/fonts/X11/misc/2xProTamsyn_r400-11.pcf.gz
```

# usage
Xresources string:
```
-nil-2xProTamsyn-medium-r-normal--22-220-72-72-c-120-iso8859-1
```

Xft string:
```
ProTamsyn2x:pixelsize=24:antialias=false:hinting=false
```

# license
refer to [ProFont](http://tobiasjung.name/profont/) and
[Tamsyn](http://www.fial.com/~scott/tamsyn-font/) licenses
