# ergodox-layouts

To use, download the qmk firmware project, and create a new directory under
"layouts/ergodox" named "yourfirmware" or whatever. Add the keymap.c file to
that directory, and then from the root of the project, type 

    $ make ergodox_ez:yourfirmware

Copy the resulting .hex file out to some location where you can easily access
it, and then flash it to your keyboard as you would any other ergodox-ez
layout file.
