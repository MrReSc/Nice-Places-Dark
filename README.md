# Nice-Places-Dark
Simple icons to replace the «place icons» (music, downloads, etc.) of Adwaita. Works best with the Adwaita dark theme on Fedora (or any distro with Adwaita as default theme).
All symbols used are the original [Adwaita symbols](https://gitlab.gnome.org/GNOME/adwaita-icon-theme/-/tree/master/Adwaita) and all are scalable `svg`. If you use a file manager or a programme that requires `png` for those icons, then problems may occur.

The basic idea is that only the «place icons» are replaced and all other icons are inherited from the Adwaita theme. If Adwaita is not installed, the icons are inherited from the `hicolor` theme. The `hicolor` theme should be implemented by every operating system. It should also work with other distributions such as Ubuntu.

The inheritance can be adjusted in the file `theme.index` if necessary. For example, as follows:
```
Inherits=Breez,hicolor
```
The last inheritance must always be the `hicolor` theme. 

The colours used are from the `GNOME HIG Colors` palette by Incscape. So the colours should fit well with a GNOME desktop environment.

## Install
Open a terminal and clone the repository:
```
mkdir -p ~/.icons
cd ~/.icons
git clone https://github.com/MrReSc/Nice-Places-Dark.git
```
Now open `gnome-tweak-tool` and change the icon theme.

## Screenshot

![](screenshots/screenshot_1.png)

