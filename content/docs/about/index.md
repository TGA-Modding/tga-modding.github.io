---
title: 'About the game'
date: 2019-02-11T19:27:37+10:00
weight: 5
---

The Glitched Attraction is a FNaF fangame made by PowerLine Studios. It is built with Unity and compiled with Mono, meaning it is relatively easy to make mods for.
All of the main game assets are stored in a single asset bundle, `data.unity3d`, as the game loads in the level around you rather than transporting you between scenes*.
All of the C# code for the game is stored in the `Assembly-CSharp.dll` file, and can be easily decompiled with a tool like [dnSpy](https://github.com/dnSpy/dnSpy)

*The game does transport ypu between scenes sometimes, but the majority of loading is done around the player.

The game stores all achievements, settings, progress etc. using Unity's PlayerPrefs system, which is not ideal as it uses the Windows registry to store data. If you want to have a closer look at the save data, you can use the [Save File Mod](https://github.com/TGA-Modding/TGA-SaveFile) to store all data in a JSON file. (this will not carry over any previous game progress).

If you want to have a look at how the game works behind the scenes, you can have a look with [Unity Explorer](https://github.com/sinai-dev/UnityExplorer). (Make sure to get the BepInEx 6 Mono version)