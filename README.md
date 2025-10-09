# Gnome Characters Quick Copy

![screenshot 3.png](data/screenshots/screenshot%203.png)

Characters Quick Copy is a customization of the original Gnome Characters desktop app. 

It allows you to quickly find the character you are looking for by searching for keywords and copy the choosen character to your clipboard with the simple and intuitive click of a the mouse, therefore skipping the character info dialog box.

You can still open the character info dialog box by CTRL-clicking on the character. 

## Helpful Links
 * [Browse source code in Git version control](https://github.com/francescogarbin/gnome-characters-)
 * [Learn more about Characters](https://apps.gnome.org/Characters/)

## Building

Characters is built using meson:
```sh
meson --prefix=/usr build
ninja -C build
sudo ninja -C build install
```

## License

Files from [gtk-js-app](https://github.com/gcampax/gtk-js-app) are
licensed under 3-clause BSD.  Other files are GPL 2.0 or later.
