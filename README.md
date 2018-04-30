# gnome-osc-themes

### GNOME-OSC-Traditional/ Gnome-OSC-traditional-light-menu and its No Transparency-versions
### GNOME-OSC-HS / Gnome-OSC-HS-light-menu and its no transparency versions
### GNOME-OSC-Space-grey and its no transparency version

![s](https://cn.pling.com/img/6/2/2/c/0c9a24b63ffa8dd5e2638df760566c43c6c9.jpg)


This is a gnome-desktop-interpretation of a certain Cupertino-based OS. I've tried to implement the feel of it on the gnome-applications, without really copying it (to prevent copyright-issues). In the latest version I've modernized it in every little detail. There is nothing (not a single item) that is not new. Resulting in a completely rewritten GTK.CSS-file four times bigger than the previous one, while the theme feels more responsive. I've also added a new dark theme (Space-grey) , so Terminal, Photo's, and Video's are automatically dark-themed.

Gnome-OSC-Space-Grey is also available seperately. This has the benefit of GTK 2.0- theming also.
Added the HS-variant too.
New: Traditional and HS come with a variant that uses light background for menu's. Useful for those with bad ( blueish )screens, since menu's tend to be blue instead of grey.

I've spend a great deal of time (3 months) and effort on this theme into fine-tuning it, so I hope you try before you judge !

## Main features:

- Support for dark theme.(Space grey)
- Use of gradients and shadows to improve readability.
- Same theming across GTK2 and GTK3. (See screenshots).

Separate download for Shell-themes:
- New Shell-theme to complement the Space-grey-variant
- Shell theme with white dock and slighty dark top-bar
- Shell theme with dark dock and dark top-bar.

This theme is developed on gnome 3.20 and updated to 3.28
This only works on a gnome-desktop, no support for other desktop-environments.
It also works on Ubuntu 18.04

When, as such, theming does not look the way it should be: make sure you have installed the necessary theme-"engines":

- The gnome-themes-standard package,
- The murrine engine. This has different names depending on your distro.
gtk-engine-murrine (Arch Linux)
gtk2-engines-murrine (Debian, Ubuntu, elementary OS)
gtk-murrine-engine (Fedora)
gtk2-engine-murrine (openSUSE)
gtk-engines-murrine (Gentoo)

sudo apt-get install gtk2-engines-pixbuf is the terminal command, usually solves the issues with GTK2.

## How to install:

First: Download the file; extract it; and you will find two themes. a version with transparency, another with (not-transparent); copy both files to a '.themes'-folder you make in your home directory. Or to your USR/SHARE/THEMES-folder for system-wide use (certainly for theming of SNAP-packages)
Then use Tweak-tool to select the GTK and shell theme.
LOG OUT AND BACK IN for changes to take effect !

Second: OSX uses titlebuttons on the left-side:
To put the buttons to the left open a terminal:

gsettings set org.gnome.desktop.wm.preferences button-layout "close,minimize,maximize:"

To put the buttons back to the right in case you want to revert:

gsettings set org.gnome.desktop.wm.preferences button-layout ":minimize,maximize,close"

In Gnome 3.26+ gnome-tweak has a option to change the position of the titlebuttons, so the above steps are not necessary. 

