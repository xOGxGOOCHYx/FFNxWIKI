# 1.7.0
Full commit list since last stable release: https://github.com/julianxhokaxhiu/FFNx/compare/1.6.1...1.7.0

This release would have never been possible without the great help of [myst6re](https://github.com/myst6re) and [sithlord48](https://github.com/sithlord48) which has now become contributors to this project. Thank you from the deep of my heart!

Please note also **the license has now been fixed to** use **GPLv3** as per [Aali own will](https://github.com/Aali132/ff7_opengl/blob/master/LICENSE).

This means that the MIT license **WAS WRONG AND WAS NEVER** compatible with GPLv3. Please make sure you understand this before claiming this code under MIT License until this point. This was a mistake that has been fixed starting this release, but this whole code has always been GPLv3 anyway.

## Common
- **NEW:** Re-worked Music Engine with full support for Winamp plugins, allowing you to play even the most esoteric extensions and having way better experience in playback while playing. Additionally the music will not be stopped when the game window will lose focus. Kudos to [myst6re](https://github.com/myst6re) for this great enhancement!
- **NEW:** Antialiasing support up to 16x!
- **NEW:** Hext by [DLPB](https://forums.qhimm.com/index.php?action=profile;u=6439) patching support now built-in! No external DLLs/EXEs required. Just put your hext files in `hext/`
- **NEW:** Override logic support! You can now override any file in `data/` by just copying it to `override/` folder instead ( path can be changed in the config file )
- **NEW:** The driver can now work if you forget to copy the config file. If not found, it will use its own default flags.
- **NEW:** Savegames will now be preserved when playing with your Steam copy. No more lost save files between multiple game sessions!
- **NEW:** Add support for 4GB LAA processes! Use up to 3.5GB of RAM space in your game for the ultimate modding experience.
- **NEW:** Improved RAM detection for the game, with much better stats shown.
- **FIX:** Improved a bit the rendering quality for external textures that do have mipmaps ( DDS only ).
- **FIX:** The driver will now work correctly even in non-standard DPI settings!
- **FIX:** The game will no more crash when closing, while a music is being reproduced.
- **FIX:** The driver is more resilient to crashes, thanks for a reworked texture memory management. This will allow you to play even heavy mods with little to no crashes. No more 1GB hard cap in RAM for textures!
- **MINOR:** You can now customize the `direct/` path in your config.
- **MINOR:** Show the driver version by default.

## FF7
- **NEW:** Fields are now vertically centered!
- **NEW:** Battles are now full screen!
- **NEW:** Menu hand cursor is now vertically aligned in the middle in menu!
- **NEW:** XInput support OOB for Xbox 360 and compatible gamepads!
- **NEW:** Movies will continue to reproduce even when the window will lose focus. No more black videos in the middle of a scene :)
- **NEW:** Movies will now reproduce respecting the overall in-game music volume.
- **NEW:** The driver now supports the [Satsuki Speedhack](https://forums.qhimm.com/index.php?topic=18851.0) mod!
- **NEW:** The driver now by default, is able to autodetect the best music settings based on your game folder structure. This can still be overridden through the config.
- **NEW:** The driver will now use correct FPS settings around the whole game: this improves minigames speed, battle swirls when vsync is off, etc.
- **NEW:** Thanks to the new music engine, it is now possible to replace wav files too! Kudos to [myst6re](https://github.com/myst6re) for this great enhancement!
- **NEW:** Thanks to the new music engine, music now will pause and resume correctly after a battle! Kudos to [myst6re](https://github.com/myst6re) for this great enhancement!
- **FIX:** Savegame crashes will now be saved in the Steam user directory, when using your Steam copy. Will still be saved in the `save/` directory on the 1998/eStore edition.
- **FIX:** Sound and music volume configuration being done in your Steam copy, are now correctly saved ( and loaded ) in your Steam user directory.
 - **FIX:** Fixed a game bug which stopped the music sometimes, known as MULCK bug (for example: Reno first encounter). Kudos to [myst6re](https://github.com/myst6re) for this great patch!

## FF8
- **NEW:** Thanks to the new music layer, it is now possible to override in-game Midi music files! Kudos to [myst6re](https://github.com/myst6re) for this great enhancement!
- **NEW:** Field Music is now correctly resumed after Triple Triad mini game. Kudos to [myst6re](https://github.com/myst6re) for this great enhancement!

If you appreciate what is being done, and what has been done so far, feel free to donate through the [Sponsoring](https://github.com/sponsors/julianxhokaxhiu) program here on Github.

---

**PLEASE NOTE:**
1. If you did use this driver in the past and you had to move files around, the game **will still work** but if you prefer to have a clean installation feel free to do so.
2. It is MANDATORY to use the given default config file, as this release has A LOT of NEW flags. Using the old config will most probably end up in unexpected behaviors.
