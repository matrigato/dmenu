matrigato's build of dmenu
============================

dmenu - dynamic menu
------------
[dmenu](https://tools.suckless.org/dmenu/) is an efficient dynamic menu for X.


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

	make clean install


Running dmenu
-------------
See the man page for details.

License
------------
In jurisdictions that recognize copyright laws, the following licenses apply:

[dmenu](https://git.suckless.org/dmenu/) is available under the [MIT/X Consortium License](LICENSES/MIT).

Everything made by me is under [The Unlicense](LICENSES/UNLICENSE).