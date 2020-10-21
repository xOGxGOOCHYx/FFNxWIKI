# Features

## For users

### FF7/FF8

- [/LARGEADDRESSAWARE](https://docs.microsoft.com/en-us/cpp/build/reference/largeaddressaware-handle-large-addresses?view=vs-2019) support!

  Up to 3.5GB of space available for mods ( this requires the [4GB Patch](https://ntcore.com/?page_id=371) in your ff7.exe ).
- High DPI support!
- Up to 16x Anisotropic support!
- Up to 16x Antialiasing support!
- Steam support! No Game converter required.
- Steam savegame preservation ( you will no more loose saves created with FFNx! )
- XInput controller support (Xbox 360 and compatible ones) with D-Pad working out-of-the-box!
- Native speedhack support!
- The game will continue to run when not in focus in Window mode

### FF7
- eStore support! No Game converter required.
- Vertical centering for Fields and Movies
- Fullscreen Battle scenes
- Menu cursor on the middle of words vertical alignment
- Movies will continue to play if the window game loses focus ( in window mode )
- Movies volume will respect global sound volume
- Steam sound and music volume configuration preservation ( configure at your pleasure and on the next run it will be inherited )
- Configurable background transparency in battle dialogs ( by default set to 75% )!
- SFX volume change will now apply in real-time, instead of you requiring to close and re-open the game.
- Support for animated textures ( like Aerith waterfall, light fading, etc. )
- Support for soft-reset while you're playing, like on the PSX!
- Support for battle toggle ( enable/disable at your own pleasure )
- Save everywhere! You are no more required to stay next to crystals in order to keep your progress.
- **Voice acting**! One of the first mods to make use of this will be [Echo-S](https://forum.tsunamods.com/viewtopic.php?f=65&t=9) when it will be released!
- Support for external SFX audio effects

### FF8
- Enable the VRAM debug window while playing in order to see how the engine uploads textures

## For Modders

- Game rendering inspection through [RenderDoc](https://renderdoc.org/)!
- [DDS Texture support](https://beyondskyrim.org/tutorials/the-dds-texture-format) up to BC7 format, with PNG Texture support as fallback.
- Support for configurable external textures path using [mod_path](misc/FFNx.toml#L100)
- Support for an override layer of the data directory using [override_path](misc/FFNx.toml#L116)
- Support for MINIPSF audio files using the emulated PSX/PS2 AKAO Engine
- Support for [Hext](https://forums.qhimm.com/index.php?topic=13574.0) patching files inside of the [hext_patching_path](misc/FFNx.toml#L113)
- Debug in-game engine data through [imgui](https://github.com/ocornut/imgui) integration.
