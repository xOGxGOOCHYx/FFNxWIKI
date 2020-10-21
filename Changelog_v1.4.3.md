# 1.4.3
Full commit list since last stable release: https://github.com/julianxhokaxhiu/FFNx/compare/1.4.2...1.4.3

## Common
- **NEW:** This release now provides three different ZIPs based on which game version you are interested. Feel free to check [installation instructions](https://github.com/julianxhokaxhiu/FFNx#how-to-install) to know which one to download.
- **NEW:** `FFNx.cfg` file has now documented all the available flags. **[With great power comes great responsibility](https://en.wikipedia.org/wiki/With_great_power_comes_great_responsibility)**
- **FIX:** Framebuffer copy operation. Now the driver will correctly copy the last seen frame, fixing the "jumping" behavior between what was used in battle swirls and what was seen before the effect started.

## FF7
- **FIX:** Fix H.264 movie playback with NAL Bitstream filters. This finally fixes 7h compatibility with Satsuki Movie mod.

## FF8
- **NEW:** Added a new `.reg` file for FF8 2000 release. This one will set the best Graphics settings which are used as well on Steam release.
- **NEW:** FF8 Battleswirls animations are now consistent with official releases. No more hacks on how they are drawn.
- **FIX:** Alpha blending operation is now correctly handled as it should be. This also fixes black borders in FF8 horizon battlefields textures.
- **FIX:** In FF8 sometimes some scenes were having some weird polygons drawn on screen. This case has now been fixed.
- **FIX:** FF8 Boss battleswirls now do show and work properly.
- **FIX:** Fix a potential crash that was happening during Squall vs Edea scene by the end of Disk 1.
- **FIX:** Sometimes movies were having some gray bars on top and on bottom, on 2000 release. This now has been fixed and black bars are always shown.
- **FIX:** FIx wrong alpha channels used in some places ( Dialog boxes background, elevator glasses and initial Squall dormitory scene ). Now it will inherit the right one. You will notice darker elevator glasses for example.

## FF8 Steam
- **NEW:** Use high resolution fonts by default.

---

**PLEASE NOTE:**
1. If you did use this driver in the past and you had to move files around, the game **will still work** but if you prefer to have a clean installation feel free to do so.
