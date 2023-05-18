# Hebrew keyboard layout with Dvorak layer for modifier keys.

## Why?

MacOS non-Latin keyboard-layouts (such as Arabic, Hebrew and many others) use the QWERTY layer for modifier keys (Command/Fn/Shift/Capslock).


This means that as a user of Dvorak and Hebrew layouts, one have to use different application hot-keys depending on the currenty layout.

For example, if you are using the Hebrew keyboard that comes with macOS and you hit Cmd+L in Firefox/Chrome, then instead of setting the focus to the address bar, the Print dialogue will show up.

That happens because the 'L' key in the Dvorak layout maps to the 'P' key in the QWERTY layout, which the default Hebrew keyboard uses for its modifier key.


By using the same modifier keys layout, you no longer have to constantly be aware of the currently selected language when triggering keyboard shortcuts, which in most applications are not language specific.

## Installation

```
$ sudo cp hebrew-dvorak.keylayout '/Library/Keyboard Layouts/'
```

Go to `System Preferences -> Keyboard -> Input Sources`, add a new input source (`+` button) and all the way down the list, under `Others`, you should find "Hebrew Dvorak".

