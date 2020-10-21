# Next

Full commit list since last stable release: https://github.com/julianxhokaxhiu/FFNx/compare/1.8.1...master

- Allow multiple fallback extensions logic for external_sfx/music/voice
- Allow native D-Pad support for DInput pads. No external tools required.
- Use DirectX APIs for Direct Input gamepads, instead of Windows Multimedia APIs. Now supporting even more gamepads than before!
- Add support for SFX sequential mode: playback every effect sequentially from being to end, and repeat
- Sound, Music and Voice layers now use VGMStream: this greatly improves codec support but also performance while playing
- Allow aspect ratio to be toggled on the fly via shortcuts
- FF7: Auto-advance message boxes when using voice acting mods.
- FF7: Prevent movie skip in certain fields to avoid game crashes.
- FF7: Allow custom Battle music replacement in Fields. Lookup order: Battle ID ( eg. `bat_391` ) -> Field Name ( eg. `bat_colne_b3`) -> Default battle music file
- FF7: Allow custom Field music replacement. Lookup order: Field ID ( eg. `field_371` ) -> Default field music file
- FF7: Various external music fixes to improve fading and volume transitions.
- FF7: External SFX files that were supposed to loop, now do loop correctly ( elevator scene for eg. )
- FF7: Voice acting volume is now always loud and clear compared to music volume even when on 100%
- FF7: Add support for 30 FPS movies or higher framerates
- FF7: Speedhack will be auto-disabled when a movie starts to prevent some bugs appearing at the end of it
- FF8: Introduce music cross fade when external music is being used.
- FF8 Steam: `ff8input.cfg` will now be loaded from `Documents\Square Enix\FINAL FANTASY VIII Steam` inheriting the original Steam driver path
- FF8: Add support for movie skip gamehack
- FF8: Add support for battle toggle gamehack
- FF8: Add support to skip the credits screen using the movie skip shortcut
- FF8: Various external music fixes to improve fading and volume transitions.
- FF8: Fix CD-ROM drive detection when the CD has been inserted after the game has already been started.
