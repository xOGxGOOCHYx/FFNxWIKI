# How-to: Install

Indendently of the way you decide to install FFNx, in order to use it you MUST have a legal copy of the game. Support will NOT be provided if the game will NOT be detected as genuine.

## Canary vs Stable

FFNx comes in two flavors, resembling the Google Chrome release names. Unlike this one though, we don't need all the others.

- **Stable:** this is a fully tested, and hopefully, bug free release.
  > It is commonly accepted for long gameplay sessions and generic users. If in doubt, use this one first.
- **Canary:** this is like a nightly release, but untested. Feel free to use it at your own risk.
  > This is what users need to try before reporting any issue encountered in this channel, or if you want to try the latest development updates going on in FFNx.

## Standalone

### Final Fantasy VII

**Supported Languages:** EN, DE, FR, SP, JP\*

> \*: Japanese support is currently work in progress. The game starts fine but font is not rendering properly and battles do crash sometimes.

#### [1998 Eidos Release](https://www.mobygames.com/game/windows/final-fantasy-vii)

1. Install the game on this path: `C:\Games\Final Fantasy VII`
2. Update your game to v1.02 ( https://www.gamefront.com/games/final-fantasy-7-advent-children/file/final-fantasy-7-retail-v1-02-patch )
3. Download the latest `FFNx-FF7_1998` release here: https://github.com/julianxhokaxhiu/FFNx/releases
4. Extract the ZIP content next to `ff7.exe` file
5. Double click on [`FFNx.reg`](https://github.com/julianxhokaxhiu/FFNx/blob/master/misc/FF7.reg)
6. Click on Yes.
7. Enjoy!

#### [2013 Steam Release](https://store.steampowered.com/app/39140/FINAL_FANTASY_VII/)

0. Install the game using Steam Client
1. Make sure you run at least your game once ( until the new game screen )
2. Open the installation directory of the game ( see [How to access game files](https://steamcommunity.com/sharedfiles/filedetails/?id=760447682) )
3. Download the latest `FFNx-Steam` release here: https://github.com/julianxhokaxhiu/FFNx/releases
4. Extract the ZIP content next to your `ff7_*.exe` file ( for eg. for EN language `ff7_en.exe`)
5. Replace all files when asked.
6. Enjoy!

#### [2013 eStore Release](http://www.jp.square-enix.com/ffvii-pc-jp/)

1. Install the game using eStore installer.
2. Open the installation directory of the game
3. Download the latest `FFNx-Steam` release here: https://github.com/julianxhokaxhiu/FFNx/releases
4. Extract the ZIP content next to your `ff7_*.exe` file ( for eg. for EN language `ff7_en.exe`)
5. Replace all files when asked.
6. Enjoy!

#### [Android Release](https://play.google.com/store/apps/details?id=com.square_enix.android_googleplay.FFVII)

1. Install the game in your Android device.
2. Locate the OBB file ( usually in `Android/obb` or `/obb` in your internal storage )
3. Save the OBB file in your Windows desktop
4. Rename the OBB file extension from `.obb` to `.zip` and extract it
5. In the extracted folder, go to `ff7_1.02` directory
6. Download the latest `FFNx-Steam` release here: https://github.com/julianxhokaxhiu/FFNx/releases
7. Extract the ZIP content next to the `ff7_*.exe` files
8. Update `FFNx.toml` flags with these values:

```toml
ffmpeg_video_ext = "webm"
external_music_path = "data/music_2"
external_music_ext = "akb"
```

9. You can now run any `ff7_*.exe` file you prefer. Enjoy!

### Final Fantasy VIII

**Supported Languages:** EN, DE, FR, SP, IT, JP

#### [2000 Squaresoft Release](https://www.mobygames.com/game/windows/final-fantasy-viii)

1. Install the game on this path: `C:\Games\Final Fantasy VIII`
2. Update your game to v1.2 ( search for `ff8_1.2.zip` or `ff8_1.2G.zip` here http://forums.qhimm.com/index.php?topic=12909.msg180223#msg180223 )
3. Download the latest `FFNx-FF8_2000` release here: https://github.com/julianxhokaxhiu/FFNx/releases
4. Extract the ZIP content next to `ff8.exe` file
5. Double click on [`FFNx.reg`](https://github.com/julianxhokaxhiu/FFNx/blob/master/misc/FF8.reg)
6. Enjoy!

#### [2013 Steam Release](https://store.steampowered.com/app/39150/FINAL_FANTASY_VIII/)

0. Install the game using Steam Client
1. Make sure you run at least your game once ( until the new game screen )
2. Open the installation directory of the game ( see [How to access game files](https://steamcommunity.com/sharedfiles/filedetails/?id=760447682) )
3. Download the latest `FFNx-Steam` release here: https://github.com/julianxhokaxhiu/FFNx/releases
4. Extract the ZIP content next to your `ff8_*.exe` file ( for eg. for EN language `ff8_en.exe`)
5. Replace all files when asked.
6. Enjoy!

## 7thHeaven 2.2.3+

> Please remember: **by updating the driver you ACCEPT to lose support from the 7thHeaven team**. Instead **limited support** will be provided through the supported FFNx [Support channels](https://github.com/julianxhokaxhiu/FFNx#Support) ONLY RELATED to driver issues.

**WARNING!** It is possible to update FFNx on 7thHeaven but after doing so you **will lose** the ability to configure the driver from 7th. Instead, you'll need to customize **manually** the driver by editing the `FFNx.toml` configuration file.

Additionally you MAY have unexpected crashes with mods not being ready yet for the latest FFNx version. **USE AT YOUR OWN RISK!**

0. Download the latest `FFNx-FF7_1998` release here: https://github.com/julianxhokaxhiu/FFNx/releases
1. Extract the ZIP content inside the `7thHeaven\Resources\Game Driver` installation directory and replace everything
2. Extract the ZIP content inside the 7th game folder directory ( next to `ff7.exe` ) and replace everything
3. In the 7th Game Folder enter `hext` and delete the `ff8` folder
4. Enter the `ff7` folder and delete every language BUT NOT `en`
5. Enter `en` and delete every file BUT NOT `FFNx.FIELD.vertical_center`
6. Enjoy!

You can hit Play as usual and enjoy the latest FFNx driver performance and bug fixes on top of 7thHeaven.
