# 1.6.0
Full commit list since last stable release: https://github.com/julianxhokaxhiu/FFNx/compare/1.5.5...1.6.0

## Common
- **NEW:** FFMpeg can now load any video file, depending on the extension you provide. See [the relative flag](https://github.com/julianxhokaxhiu/FFNx/blob/master/misc/FFNx.cfg#L78) for more information!
- **NEW:** MUCH BETTER Stack traces in your logs, giving you exact offset of all the functions being called, even inside the FF7/FF8 process.
- **MINOR:** Updated third party dependencies to their latest respective commits. May bring little to none performance improvements.
- **MINOR:** Updated config file with more instructions on how to enable/disabled flags.
- **MINOR:** Re-organized some flags in the config file. IT IS HIGHLY SUGGESTED to use the given default and update your settings again, at your wish.

## FF7 / eStore / Steam
- **NEW:** [eStore](https://github.com/julianxhokaxhiu/FFNx#2013-estore-release) support!
- **NEW:** Add [AnyCD](http://forums.qhimm.com/index.php?topic=11564.0) support for FR/DE/SP languages.
- **NEW:** [Ficedula FF7Music](http://ff8.fr/pub/FF7Music.zip) support! You can now use it to playback your in-game music, like PSF files. Because of this, [the relative existing flag](https://github.com/julianxhokaxhiu/FFNx/blob/master/misc/FFNx.cfg#L145) was updated to support this new engine.
- **NEW:** VGMStream can now load new music files, not only OGG. For a list of supported extensions see [the relative entry](https://github.com/julianxhokaxhiu/FFNx/blob/master/misc/FFNx.cfg#L162) in the config file!
- **NEW:** Initial eStore Japanese support! Please check [the relative note](https://github.com/julianxhokaxhiu/FFNx#final-fantasy-vii) for more information.
- **NEW:** Fullscreen Battle scenes! For more information feel free to check [the relative entry](https://github.com/julianxhokaxhiu/FFNx/blob/master/misc/FFNx.cfg#L178) in the config file. Kudos to [satsuki](http://forums.qhimm.com/index.php?action=profile;u=24647) and [Chrysalis](http://forums.qhimm.com/index.php?action=profile;u=674) for the help.
- **NEW:** Minor vertical alignment for the hand cursor in the Menu screen! For more information feel free to check [the relative entry](https://github.com/julianxhokaxhiu/FFNx/blob/master/misc/FFNx.cfg#L181) in the config file.
- **MINOR:** You can now disable the Field vertical centering if you want, through [the relative flag](https://github.com/julianxhokaxhiu/FFNx/blob/master/misc/FFNx.cfg#L175).
- **FIX:** Steam SP was crashing on launch. This has now been fixed.
- **FIX:** Field vertical centering in FR was having graphical glitches. This now has been fixed.
- **FIX:** Fix potential crash happening while closing the game, meanwhile the audio was being reproduced using VGMStream.

And remember, if you like this project please consider [Sponsoring](https://github.com/sponsors/julianxhokaxhiu) me. This will greatly help in moving the project even further.

---

**PLEASE NOTE:**
1. If you did use this driver in the past and you had to move files around, the game **will still work** but if you prefer to have a clean installation feel free to do so.
2. It is HIGHLY suggested to use the given default config file, as this released moved A LOT of flags around and gave them new options.

# 1.5.5
Full commit list since last stable release: https://github.com/julianxhokaxhiu/FFNx/compare/1.5.4...1.5.5

## FF7 + FF7 Steam
- **NEW:** Movies and Field scenes are now vertically centered.

---

**PLEASE NOTE:**
1. If you did use this driver in the past and you had to move files around, the game **will still work** but if you prefer to have a clean installation feel free to do so.
