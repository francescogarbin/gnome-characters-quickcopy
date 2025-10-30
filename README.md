# Gnome Characters Quick Copy

![screenshot 3.png](data/screenshots/screenshot%203.png)

Characters Quick Copy is a customization of the original Gnome Characters desktop app.

It allows you to quickly find the character you are looking for by searching for keywords and copy the choosen character to your clipboard with the simple and intuitive click of a the mouse, therefore skipping the character info dialog box.

You can still open the character info dialog box by CTRL-clicking on the character. 

## Helpful Links
 * [Browse source code in Git version control](https://github.com/francescogarbin/gnome-characters-quickcopy)
 * [Learn more about Characters](https://apps.gnome.org/Characters/)

## Building

Characters is built using meson and requires quick dependences, I found parti

Install a few packages for the project to build.

```sh
sudo dnf update  
sudo dnf install gjs-devel gtk4-devel libadwaita-devel \
                 gobject-introspection-devel desktop-file-utils \
                 appstream gettext
```

Then build with meson and install with ninja.

```sh
meson --prefix=/usr build
ninja -C build
sudo ninja -C build install
```

## License

This code is licensed under GPL 2.0 or later.

Files from the [read-only mirror](https://github.com/GNOME/gnome-characters) of the original Gnome Charactoer app
are licensed under the BSD-3-Clause license. 

## Credits

This project exists thanks to all the [people who contribute](https://github.com/GNOME/gnome-characters/graphs/contributors) to the original Gnome Characters app.
