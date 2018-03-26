# Config files for using German Umlaut on non-German keyboards
... using the CAPS lock key as a meta key

.xmodmap.uk was edited manually, then converted to the xkbmap following the instructions at https://askubuntu.com/questions/325272/permanent-xmodmap-in-ubuntu-13-04/858272#858272

1. `xmodmap .xmodmaprc.uk`
2. `xkbcomp $DISPLAY .xkbmap`
3. `echo 'xkbcomp $HOME/.xkbmap $DISPLAY' >> ~/.bashrc`


