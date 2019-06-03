# New Vegas Modding

### My personal (and IMHO, amazing) modpack for *"Fallout: New Vegas"*

### Contains:
* **Documentation**
* **INI Tweaks**
* **NVSE**
* **LOOT**
* **New Vegas Configurator**
* **4GB Patch**
* **All NVSE Plugins**
* **All Mods**
* **Every Asset Required**

----

## [DOWNLOAD](https://github.com/Snowynx/new-vegas-modding/releases/download/dist/newvegasmodding.zip)

----

## [LICENSE](./LICENSE.txt)

----

## General Notes

### Run the game once to create registry keys, and to fill the "IStewieAI Tweaks" and "OneTweak" INI configuration files with (more) options (which you can edit yourself) <br><br> I did **not** create **ANYTHING** you download here, with the exception of the distribution file, which I packaged together myself in my own free-time <br><br> Mods in the distribution file will be updated monthly (if they require updates)

----

## [INI Notes](./ININotes.md)

----

## Installation
**Copy-paste everything into your *New Vegas* directory. <u>DO NOT</u> override ANYTHING, and instead, MERGE**

**Then, use LOOT to put everything into the proper load order to avoid conflicts/problems, and to generate your data `.txt` file which *New Vegas* will use to load the base game, all DLCs, and all your mods**

----

## INI Tweaks

### Create a file named `"FalloutCustom.ini"` in `Documents/My Games/FalloutNV` <br><br> Paste all the tweaks below into `FalloutCustom.ini`, which is used and implemented by the JIP LN NVSE Plugin <br><br> These INI tweaks are used to have the best game experience with minimal crashing

```fix
[General]
bUseThreadedAI=1
iNumHWThreads=4
bUseMultiThreadedFaceGen=1
bUseMultiThreadedTrees=1
bLoadFaceGenHeadEGTFiles=1
bPreemptivelyUnloadCells=1
bUseThreadedBlood=1
bUseThreadedMorpher=1
bUseThreadedTempEffects=1
bUseThreadedParticleSystem=1

[BackgroundLoad]
bBackgroundCellLoads=1
bSelectivePurgeUnusedOnFastTravel=1

[Display]
fLightLODDefaultStartFade=10240.0
fLightLODRange=10240.0
fLightLODMinStartFade=10240.0
fLightLODMaxStartFade=10240.0
fShadowLODDefaultStartFade=200.0
fShadowLODRange=200.0
fShadowLODMinStartFade=100.0
fShadowLODMaxStartFade=1000.0
fSpecularLODDefaultStartFade=10240.0
fSpecularLODRange=10240.0
fSpecularLODMinStartFade=10240.0
fSpecularLODMaxStartFade=10240.0
iPresentInterval=0

[Controls]
fForegroundMouseAccelBase=0
fForegroundMouseAccelTop=0
fForegroundMouseBase=0
fForegroundMouseMult=0
fXenonVertLookSpeed=1200.0000
fXenonHorizLookSpeed=1500.0000

[Grass]
fGrassStartFadeDistance=17000

[Audio]
iAudioCacheSize=8192
iMaxSizeForCachedSound=2048
```
> **Note: `iNumHWThreads` should be the amount of physical CPU cores you have**

----

## [*New Vegas* Configurator](https://www.nexusmods.com/newvegas/mods/40442)

**Use this to configure *New Vegas* without messing around with INI files dangerously**

----

## Not mods or NVSE plugins, but required for modding or performance

[LOOT](https://loot.github.io)

> **Used for manual installation and proper load order to avoid conflicts/problems**

[NVSE](http://nvse.silverlock.org/download/nvse_5_1_beta4.7z)

> **Allows the majority of mods to be used by extending scripts and script functions which mods require to work**

[4GB Patch](https://www.nexusmods.com/newvegas/mods/62552)

> **RAM that *New Vegas* can use is increased from 2GB to 4GB for modding and performance**

----

## Mods and NVSE Plugins 

[JIP LN NVSE PLUGIN](http://www.nexusmods.com/newvegas/mods/58277)

> **Adds lots of extra functions mods can use**

[NVAC](http://www.nexusmods.com/newvegas/mods/53635)

[NVSR](https://www.nexusmods.com/newvegas/mods/34832)

> **Note: Use [NVTF](https://www.nexusmods.com/newvegas/mods/66537) if you have Windows 10 or if you don't want to tweak NVSRs INI config files**

[Better first person](https://www.nexusmods.com/newvegas/mods/55334)

[OneTweak (better dynamic windows)](https://www.nexusmods.com/newvegas/mods/59266)

[User Interface Organizer](https://www.nexusmods.com/newvegas/mods/57174)

[Flashlight NVSE](https://www.nexusmods.com/newvegas/mods/39968)

[Pickup Ammo on walk-over](https://www.nexusmods.com/newvegas/mods/42634)

[Better Pickup Prompt & Enemy Hover](https://www.nexusmods.com/newvegas/mods/63091)

[Better Recipe Menu](https://www.nexusmods.com/newvegas/mods/59638)

[Weapon Mod Menu](https://www.nexusmods.com/newvegas/mods/44515)

[Tutorial Killer](https://www.nexusmods.com/newvegas/mods/47746)

[FOV Slider](https://www.nexusmods.com/newvegas/mods/55085)

[Unofficial Patch Plus](https://www.nexusmods.com/newvegas/mods/62953)

> **Note: Use the addendum and custom companion suite file as well**

[Mod Configuration Menu](https://www.nexusmods.com/newvegas/mods/42507)

[YUP Bugfix Patch](https://www.nexusmods.com/newvegas/mods/51664/?)

[CASM](https://www.nexusmods.com/newvegas/mods/45652)

[WMX](https://www.nexusmods.com/newvegas/mods/39651)

[More Perks](https://www.nexusmods.com/newvegas/mods/66510)

[JIP CC&C](https://www.nexusmods.com/newvegas/mods/50468)

[JIP Selective Fire](https://www.nexusmods.com/newvegas/mods/49478)

[Delay DLC Notifications](https://www.nexusmods.com/newvegas/mods/62779)

[Better GRA Implementation](https://www.nexusmods.com/newvegas/mods/46138)

[Useful Misc Items](https://www.nexusmods.com/newvegas/mods/59561)

[Economy Overhaul](https://www.nexusmods.com/newvegas/mods/62899)

[Vanilla UI+](https://www.moddb.com/mods/vanilla-ui-plus)

> **Use [this](https://www.nexusmods.com/newvegas/mods/67032) for more info**

[Clarity - No Orange Tint](https://www.nexusmods.com/newvegas/mods/62481)

[Simple Street Lights](http://modsreloaded.com/simple-street-lights)

[Increased Wasteland Spawns](https://www.nexusmods.com/newvegas/mods/38623)

[Enemy AI - Tactics - Healing](https://www.nexusmods.com/newvegas/mods/39058)

[DFB - Dynamic Crosshair](https://www.nexusmods.com/newvegas/mods/43550)

[Sprint Mod](https://www.nexusmods.com/newvegas/mods/66960)

[Functional play after game ending](https://www.nexusmods.com/newvegas/mods/66726)

[DFB Random Encounters](https://www.nexusmods.com/newvegas/mods/42793)

[Non unique DLC weapons in base game](https://www.nexusmods.com/newvegas/mods/47880)

[Better NPC Awareness](https://www.nexusmods.com/newvegas/mods/63425)

[Willow Companion](https://www.nexusmods.com/newvegas/mods/41779)

[Underground Hideout](https://www.nexusmods.com/newvegas/mods/37884)

[Underwater Home](https://www.nexusmods.com/newvegas/mods/36121)

> **Use Underwater Home with the [sorting overhaul and the Willow sandwich extension files](https://www.nexusmods.com/newvegas/mods/57062) and the [extended sorters](https://www.nexusmods.com/newvegas/mods/47346/)**

[Combat Enhancer](https://www.nexusmods.com/newvegas/mods/58431)

[Alternate Repairing](https://www.nexusmods.com/newvegas/mods/52510)

[Better Melee Weapon Reach](https://www.nexusmods.com/newvegas/mods/62032)

[Complete Correct Respec](https://www.nexusmods.com/newvegas/mods/59629)

[Stimpak Hotkey](https://www.nexusmods.com/newvegas/mods/64043)

[Minimap](https://www.nexusmods.com/newvegas/mods/64596)

[Inventory Sorting](https://www.nexusmods.com/newvegas/mods/63867)

[Grenade Hotkey](https://www.nexusmods.com/newvegas/mods/66686)

[Inventory Search](https://www.nexusmods.com/newvegas/mods/66329)

[More Realistic Aiming](https://www.nexusmods.com/newvegas/mods/40652)

> **Use this mod with the [sleep deprivation fix](https://www.nexusmods.com/newvegas/mods/61287)**

[Immersive Recoil](https://www.nexusmods.com/newvegas/mods/61973)

> **If you want to easily aim, DON'T USE THIS (distribution will include this, be sure to remove it if you don't want it)**

[Better Lonesome Road Allegiance](https://www.nexusmods.com/newvegas/mods/44042)

[Throwable Weapon Fixes](https://www.nexusmods.com/newvegas/mods/62767)

[Reactivated On-Hit Dialogue](https://www.nexusmods.com/newvegas/mods/64786)

[IStewieAI Tweaks](https://www.nexusmods.com/newvegas/mods/66347)

[Melee Sweeping](https://www.nexusmods.com/newvegas/mods/66187)

[No More Motion Sickness](https://www.nexusmods.com/newvegas/mods/65732)

[Retrievable Throwables](https://www.nexusmods.com/newvegas/mods/66461)

[Professionally Fixed Legion Areas](https://www.nexusmods.com/newvegas/mods/66336)

[Misc Item Icons](https://www.nexusmods.com/newvegas/mods/34737)
