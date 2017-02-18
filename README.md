# jgd-black
JGD-Black is a theme collection for GTK applications and Openbox. This collection will style your desktop with glass buttons, pure black top level menus, subtle gray shadows and borders.

With this theme package, you get GTK 2, GTK 3.20 and Openbox themes.

* [Theme homepage at Jason G. Designs](http://www.jasong-designs.com/2017/02/04/jgd-black-gtk3/)

## How to Install

1. Download the latest file from the [downloads](https://github.com/jgpws/jgd-black/tree/master/downloads) directory
2. Open a Terminal application
3. Navigate to your Downloads folder in the terminal (usually titled Downloads). Type `cd Downloads`
4. Type `ls` and look for `jgd-black-month-day-year.tar.gz`, where month, day and year represent when the file was last updated
5. Untar the file by typing `tar -zxvf jgd-black-01-01-17.tar.gz`, substituting the current version's date numbers
6. type `cd` again to get to your home folder; type `ls -a` and see if there is a **.themes** directory
7. If one does not exist, create one: `mkdir .themes`
8. `cd Downloads`
9. `cp JGD-Black ../.themes`

### To install JGD-Black globally:

1. Follow steps 1-5 above
2. `cd /usr/share/themes`
3. `sudo cp -r ~/Downloads/JGD-Black /usr/share/themes`
4. Enter sudo password
5. `ls` to check that the theme folder is present

### To install on Arch Linux:

JGD-Black is available in the Arch User Repository. The easiest way to install it is with a pacman frontend which accesses the AUR, such as [Yaourt](https://archlinux.fr/yaourt-en).

`yaourt -S jgd-black`

Once installed, you can use a theme switching application such as **LXAppearance** or **Gnome Tweak Tool** to change the theme to JGD-Black

## How to install the Clearlooks theme engine:

JGD-Black GTK2 requires the Clearlooks theme engine. To install from the command line:

### Ubuntu and derivatives:

`apt-get install gtk-engines`

### Arch Linux and derivatives:

`sudo pacman -S gtk-engines`

Note: The GTK3 version of this theme only works version 3.20 and upwards.
