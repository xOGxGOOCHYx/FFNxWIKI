# 1.5.0
Full commit list since last stable release: https://github.com/julianxhokaxhiu/FFNx/compare/1.4.5...1.5.0

## Common
- **NEW:** [DDS Texture support](https://beyondskyrim.org/tutorials/the-dds-texture-format) (up to BC7 format). Faster loading times, lower memory usage, same quality as PNG.
- **NEW:** Improved overall visual rendering output: now MUCH clearer and sharper than before.
- **NEW:** Added support for internal rendering multiplier! Scale your internal game resolution up to your pleasure, as long as your GPU can handle it :)
- **FIX:** Depth testing in D3D11/D3D12/Vulkan now working the same as with OpenGL rendering.
- **FIX:** `save_textures` flag now works as expected.
- **MINOR:** Improve Video decoding stability.
- **MINOR:** Improve texture copy operation from GPU memory.
- **MINOR:** Improve performance while getting game status mode.
- **FLAG:** Added flag to turn on/off the Anisotropic filtering.
- **FLAG:** Added flag to show/hide the Backend renderer in the window title or in fullscreen mode.
- **FLAG:** Added flag to tweak the internal renderer multiplier.
- **FLAG:** Added flag to show current FFNx version being used.

## FF7
- **FIX:** A lot of missing effects in Summons ( for eg. Kujata earthquake, or Odin cut effects )
- **FIX:** Escape materia wobbling effect.
- **FIX:** Snowboard minimage background is now white as expected.
- **FIX:** Fort Condor minigame was not clearing correctly the screen, while now it does.
- **FIX:** Battle swirls now fade correctly like on PSX.

## FF8
- **NEW:** [Unofficial bad UV texture patch by Maki](http://forums.qhimm.com/index.php?topic=16327.0) for **ALL LANGUAGES**
- **FIX:** FR GeForce version now works fine with FFNx.
- **FIX:** SP Non-GeForce version now works fine with FFNx.
- **FIX:** US Eidos GeForce/Non-GeForce versions now works fine with FFNx.

---

**PLEASE NOTE:**
1. If you did use this driver in the past and you had to move files around, the game **will still work** but if you prefer to have a clean installation feel free to do so.
