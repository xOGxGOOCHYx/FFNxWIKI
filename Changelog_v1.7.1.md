# 1.7.1
Full commit list since last stable release: https://github.com/julianxhokaxhiu/FFNx/compare/1.7.0...1.7.1

## Common
- **FIX:** FFNx is now fully compatible starting from Windows 7 and newer releases
- **FIX:** Override layer is now case-insensitive.
- **FIX:** External music is now disabled by default, with an auto-enable functionality if known music paths are detected. If not, the driver will continue to use the default engine music layer. This fixes missing MIDI sound by default.

## FF7
- **MINOR:** `FFNx.reg` will now fix your sound device to inherit the default chosen one on Windows.
- **MINOR:** FFNx will now log if your controller is detected as XInput or DInput.

If you appreciate what is being done, and what has been done so far, feel free to donate through the [Sponsoring](https://github.com/sponsors/julianxhokaxhiu) program here on Github.

---

**PLEASE NOTE:**
1. If you did use this driver in the past and you had to move files around, the game **will still work** but if you prefer to have a clean installation feel free to do so.
2. It is HIGHLY SUGGESTED to always use the given default config file. Using the old config will most probably end up in unexpected behaviors.
