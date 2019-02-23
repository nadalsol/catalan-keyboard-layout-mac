## Catalan Keyboard Layout

![Input Sources Menu](https://raw.githubusercontent.com/nadalsol/catalan-mac-keyboard-layout/master/macos-input-sources-menu.png)

Tired of staring at the Spanish flag, but still need to type with different keyboards including the Spanish character set? Then just copy the `.keylayout` and `.icns` file into `/Library/Keyboard\ Layouts/` on your Mac! You probably need to reboot and then you may choose the layout under "System Preferences > Keyboard > Input Sources".

```
$ git clone https://github.com/nadalsol/catalan-mac-keyboard-layout.git
$ cd catalan-mac-keyboard-layout/
```

Catalan layout with **senyera** flag:

```
$ sudo cp Catalan.* /Library/Keyboard\ Layouts/
```

![Senyera Flag](https://raw.githubusercontent.com/nadalsol/catalan-mac-keyboard-layout/master/flag-senyera.png)

Catalan layout with **estelada** flag:

```
$ sudo cp Catalan\ \(Estelada\).* /Library/Keyboard\ Layouts/
```

![Estelada Flag](https://raw.githubusercontent.com/nadalsol/catalan-mac-keyboard-layout/master/flag-estelada.png)

Catalan layout with **tricentenari** flag:

```
$ sudo cp Catalan\ \(Tricentenari\).* /Library/Keyboard\ Layouts/
```

![Tricentenari Flag](https://raw.githubusercontent.com/nadalsol/catalan-mac-keyboard-layout/master/flag-tricentenari.png)

### Modify the layout

Feel the need to update the layout to your liking by adding in the Catalan language characters? Download the keyboard layout tool [Ukelele](http://scripts.sil.org/ukelele) and have at it.

### Resources

* Based on the [Ukrainian-Russian](https://github.com/palmerc/Ukrainian-Russian) repo, by [palmerc](https://github.com/palmerc).
* [How to make a custom keyboard layout in OS X?](https://superuser.com/questions/665494/how-to-make-a-custom-keyboard-layout-in-os-x).
