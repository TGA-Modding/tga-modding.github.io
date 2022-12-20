---
title: "Install modding tools"
date: 2022-12-20T11:32:52Z
draft: false
weight: 100
---

To get the game loading mods, you need to install BepInEx, a mod loader. Follow the below steps:
1. Go to the GitHub [releases page](https://github.com/BepInEx/BepInEx/releases/tag/v6.0.0-pre.1), and download `BepInEx_UnityMono_x64_6.0.0-pre.1.zip`
2. Extract the contents (BepInEx, winhttp.dll, etc) into the game folder
3. Launch the game to generate files/folders
4. Check if a file called `LogOutput.log` exists in the BepInEx folder
   - If it does, carry on to step 5
   - Othewise, head to the troubleshooting section
5. You will probably want the API mod, so download the latest version from the [releases page](https://github.com/TGA-Modding/TGAPI/releases)
6. Extract the DLL file(s) into the generated `BepInEx/plugins` folder
7. Run the game
8. If everything succeeded, you should see "TGAPI Ver x.x.x" under the game version on the title screen
   - If you can see it, congrats! Everything is set up
   - If you can't, go down to the troubleshooting section
