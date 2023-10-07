# DevMiner's keymap for the Sofle v2

## IMPORTANT:

Edit the `config.h` to have the correct option for the keyboard half as on some of my keyboards it didn't quite detect which side is which.

## Changes:

-   Moved around most symbol keys on the lower layer
-   Swapped <kbd>Enter</kbd> and <kbd>Space</kbd>
-   Removed Colemak
-   Added Game mode (shifts left keyboard half by one key to the right)

## Commands:

### Build:

```shell
make sofle:vyoyo
```
The resulting `.hex` file will be in `.build/sofle_rev1_vyoyo.hex`.

### Flash:

```shell
make sofle:vyoyo:avrdude
```
