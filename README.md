# TF2 patcher to unlock equip regions

## Summary

This tool allows you to remove various restrictions when equipping cosmetic items.

In short, now you can equip any cosmetic items you'd like, even if they're conflicting!

This is a fork of the original equip region patcher, you can view it [here](https://github.com/ill5-com/tf2-equip-region-patcher). The project appears to be dead so I have updated it for the 64 bit version of TF2.

![https://i.imgur.com/hcHtRvU.jpeg](https://i.imgur.com/hcHtRvU.jpeg)

## Is it safe?

It is completely safe to use. However:

- Beware this software still patches TF2 memory. After the patching is done the program closes all open handles to TF2 (which is how VAC detects cheats). It is extremely unlikely this will be detected as it is not a cheat.

## How to use

1. Download the latest release [here](https://github.com/rsedxcftvgyhbujnkiqwe/tf2-equip-region-patcher/releases/latest);

2. Extract the bat file and exe to your TF2 directory, right next to the game's executable (tf_win64.exe)

3. Set your launch options to: `"C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\launch_patcher.bat" %command%` and launch the game

5. Equip any items you'd like!


## Building from source

Run `make TARGET=64`.

C11-aware compiler is required. 

I used mingw-w64 + msys2 for compilation.

## Linux support?
I have a Linux version of this patcher [here](https://github.com/rsedxcftvgyhbujnkiqwe/tf2-equip-region-patcher-linux)


## License

See UNLICENSE file.
