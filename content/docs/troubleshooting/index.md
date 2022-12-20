---
title: "Troubleshooting"
date: 2022-12-20T11:47:16Z
draft: false
weight: 100
---

#### If you came here because BepInEx files (LogOutput.log) aren't generating, try running through the following steps:
1. Make sure that the files are in the right place:
   - Are the `doorstop_config.ini`, `winhttp.dll`, `BepInEx` folder/files in the same folder as `UnityPlayer.dll`, `The Glitched Attraction.exe` files

2. Did you download the right version of BepInEx:
   - Even if your computer is 32-bit, you still have to download the 64-bit version of BepInEx
   - The game is Mono, so the Il2Cpp version won't work
   - If you are running the game through a compatibility layer like Wine on unix systems, you still need the Windows version

#### If you came here because the TGAPI mod isn't loading:
1. Check that the files are in the right place:
   - `TWAPI.dll` and any other DLL files shipped with the mod should all be in the `<game folder>/BepInEx/plugins` folder.
2. Try re-downloading the mod:
   - You may have downloaded a broken version, and hopefully a patch will have been released.
   - Download the latest version from [here](https://github.com/TGA-Modding/TGAPI/releases/latest)
3. Ask in the [discord server](https://discord.gg/rENUEg3MT5) for support
