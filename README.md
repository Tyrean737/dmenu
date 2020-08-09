The [suckless dynamic menu (dmenu)](https://tools.suckless.org/dmenu) with some official patches:

+ reads Xresources (adds pywal compatibility)
+ `-P` for password mode: hide user imput
+ `-r` to reject non-matching input
+ `-i` for case insesitive mode (enabled by default)

The applied official patches are stored in '/patches/main-patches/' and are combined in '/patches/dmenu-main-patches.diff'. Customization was done with
'/patches/dmenu-personalization.diff', as described in the header.


## Installation

After making any config changes that you want, but `make`, `sudo make install` it.
