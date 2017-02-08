ergoemacs-xkb
=============
ErgoEmacs-like mappings for XKB

Installation
------------
```
ln -s $(realpath types/navigation) /usr/share/X11/xkb/types
ln -s $(realpath symbols/navigation) /usr/share/X11/xkb/symbols
```
And add `navigation` to `xkb_symbols` configuration.
