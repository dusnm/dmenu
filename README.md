# My build od suckless' dmenu

## dmenu - dynamic menu
dmenu is an efficient dynamic menu for X.

## Requirements
In order to build dmenu you need Xlib header files.

## Installation
Clone the repository
```
git clone https://github.com/dusnm/dmenu.git
```
Edit config.mk to match your local setup (dmenu is installed into the /usr/local namespace by default).
Afterwards enter the following command to build and install dmenu (if necessary as root):
```
make clean install
```

## Applied patches

* border
* center
* line height

## Modifications

* Different default colors
* UbuntuMono Nerd Font
* Center and run the dmenu\_run script in list mode by default
* Commented out the fix that doesn't allow color fonts (A fix for the libxft bug is available in the AUR)
