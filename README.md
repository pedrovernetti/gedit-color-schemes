# Gedit Color Schemes

This pack contains some gedit color schemes I've made, shared under **MIT License**.

## Previews:

##### Argent

![Sample text](https://github.com/pedrovernetti/gedit-color-schemes/raw/master/Screenshots/Argent_text.png)

![Sample code](https://github.com/pedrovernetti/gedit-color-schemes/raw/master/Screenshots/Argent_code.png)

##### Eldritch

![Sample text](https://github.com/pedrovernetti/gedit-color-schemes/raw/master/Screenshots/Eldritch_text.png)

![Sample code](https://github.com/pedrovernetti/gedit-color-schemes/raw/master/Screenshots/Eldritch_code.png)

##### Wizardry

![Sample text](https://github.com/pedrovernetti/gedit-color-schemes/raw/master/Screenshots/Wizardry_text.png)

![Sample code](https://github.com/pedrovernetti/gedit-color-schemes/raw/master/Screenshots/Wizardry_code.png)

## Installation

#### Manual

Place the .xml files or links to them at `~/.local/share/gedit/styles`.
For this (placing the actual files), run:

`wget -c -O ~/pvgcs.zip https://github.com/pedrovernetti/gedit-color-schemes/archive/master.zip`

`mkdir -p ~/.local/share/gedit/styles`

`unzip -j ~/pvgcs.zip *.xml -d ~/.local/share/gedit/styles ; rm -f ~/pvgcs*`

(you may need to exit gedit and open it again)
Then, on a gedit window, go to __Edit__ > __Preferences__ > __Font & Colors__ and you will see a **Color Scheme** list. Click the desired scheme and close the Preferences window.

## Uninstall

#### For manual installations

Run:

`rm -f ~/.local/share/gedit/styles/{argent,eldritch,occult,wizardry}.xml`

## Bugs
If you find a bug, please report it at https://github.com/pedrovernetti/gedit-color-schemes/issues

## License

As said, all the schemes are available under the terms of the MIT License. See `LICENSE` for details.


