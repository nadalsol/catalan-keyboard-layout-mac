# Catalan Keyboard Layout

## Visca Catalunya!

![Input Sources Menu](https://raw.githubusercontent.com/nadalsol/catalan-mac-keyboard-layout/master/input-sources-menu.png)

Tired of staring at the Spanish flag while the Catalan independentists are being persecuted by the Government of Spain, but still need to type with different keyboards including the Spanish character set? Then just copy the `.keylayout` and `.icns` file into `/Library/Keyboard\ Layouts/` on your Mac! You probably need to reboot and then you may choose the layout under "System Preferences > Keyboard > Input Sources".

```
$ git clone https://github.com/nadalsol/catalan-mac-keyboard-layout.git
$ cd catalan-mac-keyboard-layout/
```

Catalan layout with **senyera** flag:

![Senyera Flag](https://raw.githubusercontent.com/nadalsol/catalan-mac-keyboard-layout/master/flag-senyera.png)

```
$ sudo cp Catalan.* /Library/Keyboard\ Layouts/
```

Catalan layout with **estelada** flag:

![Estelada Flag](https://raw.githubusercontent.com/nadalsol/catalan-mac-keyboard-layout/master/flag-estelada.png)

```
$ sudo cp Catalan\ \(Estelada\).* /Library/Keyboard\ Layouts/
```

Catalan layout with **tricentenari** flag:

![Tricentenari Flag](https://raw.githubusercontent.com/nadalsol/catalan-mac-keyboard-layout/master/flag-tricentenari.png)

```
$ sudo cp Catalan\ \(Tricentenari\).* /Library/Keyboard\ Layouts/
```

## Modify the layout

Feel the need to update the layout to your liking by adding in the Catalan language characters? Download the keyboard layout tool [Ukelele](http://scripts.sil.org/ukelele) and have at it.

## Inspiration

* Based on the [Ukrainian-Russian](https://github.com/palmerc/Ukrainian-Russian) repo, by [palmerc](https://github.com/palmerc).
* [How to make a custom keyboard layout in OS X?](https://superuser.com/questions/665494/how-to-make-a-custom-keyboard-layout-in-os-x).
