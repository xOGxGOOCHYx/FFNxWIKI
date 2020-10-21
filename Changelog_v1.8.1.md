# 1.8.1
Full commit list since last stable release: https://github.com/julianxhokaxhiu/FFNx/compare/1.8.0...1.8.1

### Improved stability

This release focuses on adding minor enhancements, as well as improving the stability of the driver.

Some of these changes are:
- Removed `texture_filtering` option! You don't need to tinker with it anymore. The driver will automatically detect when enabling it, or not.
- Fixed loading shuffle IDs that are not part of the core engine by default ( any ID > 750 ). You can now use **up to 10000** IDs!
- Fixed music fading on voice acting. Sometimes the volume of the music was raised higher than the currently set one in-game. Now your desire in-game volume will be considered, before fading.
- Updated third_party libraries to their latest version.
- Fixed texture dump ( `save_textures` ) on Final Fantasy 8.

---

If you appreciate what is being done, and what has been done so far, feel free to donate through the [Sponsoring](https://github.com/sponsors/julianxhokaxhiu) program here on Github.

---

**PLEASE NOTE:**
1. This release brings a **whole new** configuration file type that is **NOT** compatible with previous releases. Please make sure you install all the provided files before starting with the new FFNx.
2. It is HIGHLY SUGGESTED to always use the default config file. Using old config files will probably end up with unexpected behaviors.
