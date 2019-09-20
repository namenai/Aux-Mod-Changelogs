[green_saber]: https://i.imgur.com/dw5H790.png "Reeee"
[legacy_helm]: https://i.imgur.com/pAKSSR7.jpg "Legacy Helmet"
[arse_meme]: https://i.imgur.com/Ckt5kTh.png "Arsenal Issue"
# RE<sup>3</sup> Update Changelog <!-- omit in toc -->

>**Obi Wan** - Hello There. ![yeet][green_saber]

Remade, Renewed, Refreshed.

## Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
- [Infantry Weapons 🔫](#infantry-weapons-)
  - [Scopes](#scopes)
  - [Mod 0](#mod-0)
  - [Z6](#z6)
  - [Sidenote ⚠️](#sidenote-️)
- [Vehicles 🚗](#vehicles-)
- [Aviation ✈️](#aviation-️)
- [Particle Effects 🍄](#particle-effects-)
- [Zeus CAS Modules ⚡](#zeus-cas-modules-)
- [Low Poly Droids 🤖](#low-poly-droids-)
- [Stretcher 💉](#stretcher-)
- [Factions 🎖️](#factions-️)
- [Other 🤷](#other-)
- [Additions/Other](#additionsother)
- [Prototypes](#prototypes)
- [Jumppack 🦘](#jumppack-)
- [For other mod devs 💻](#for-other-mod-devs-)
  - [Legacy Classnames](#legacy-classnames)
  - [Arsenal Loadouts](#arsenal-loadouts)
  - [Keys](#keys)
- [Helmets ⛑️](#helmets-️)
  - [Aviation Helmets](#aviation-helmets)
  - [Infantry Helmets](#infantry-helmets)
  - [AB Helmets](#ab-helmets)
- [Clousing Remarks](#clousing-remarks)

## Introduction

Hello there 👋

The original intent of this mod update wasnt to bring new content but rather remake the entire mod for the sake of fixing bugs(🐛), improve its quality(💯/💯) and allow for easier addition of new content in the future and time(⌛). However in the 3-4 months that it took to remake the mod some new content was added, so I will first review the changes and then list out the new content to the best of my ability.

Additionaly the repo has changed its structure a little bit. This is the Aux mod github repo with changelogs/information [here.](https://github.com/namenai/Aux-Mod-Changelogs)

Finaly the R&D mod has been removed, and recombined with this mod.

## Infantry Weapons 🔫

The main changes for infantry weapons are that some insignificant digits of values where removed. For example the rate of fire on the DC-15a is `600.33333` rounds per minute,I went ahead and just made it `600` since that extra `.33333` is completly irrelevant. Additionaly I went ahead and removed the word `Custom` that was infront of every weapon and all weapons now should in arsenal have the 501st logo next to them. Weapons now uses magwells where ever possible to increase consistancy on the creation side of things. Most weapons should be with the 501st logo except for a few such as the E5, or B2 handgun for now. Now there are a few things that should be noted, the scopes, mod0, and  Z6. 🔫

### Scopes

The scopes on the DC-15a, DC-15a Gl and DC-15a Mod 0 are all now x4 becuase x3 was weird. Additionaly they all use the OG valken scope which means they now have a red dot thats not the fucking size of a MTT at 10 meters.

### Mod 0

The magazines for the Mod 0 has been changed to just be the 240 round mag. This is a temporary thing, so inorder to compensate for not having a 120rnd mag I made the 240rnd mag weigh 20% less (50 to 40, compared to the 120rnd weight of 30).

### Z6

The Z6 has a scope, sorta. Right clicking will move the camera ever so slighty towards the z6, kind of like ur moving your head but it wont be an iron sight. If you `control+right click` it will go into the same scope that the DC-15a has.

### Sidenote ⚠️

Keep in mind that I am actually working on reworking the weapons for the better, with a smol, well rather large, group of people that contain the MOS instructors to help, so just hold on till then OwO. 😎

## Vehicles 🚗

The biggest change for vehicles is that any vehicle edited has been placed into a faction. The names are `RD501 XXX Faction` where XXX is sutff like `CIS` or `Republic`. Simply look for the `RD501` header and you will be fine. Also names have been standardized a little bit, and scripts have been optimized to improve performance.

## Aviation ✈️

Added back some previous weapons that where phased out of Aerium update, for example Y Wing Voltic.

Also the LAAT naming scheme has been remade, just add +2 to the name so LAAT Mk.I is now LAAT Mk.III and LAAT Mk.II is now LAAT Mk.IV

## Particle Effects 🍄

Unfortunatly due to time, I have had to remove almost all particle effects becuase I simply didnt have the time to review them all. In time I will redo them all and add them back.

## Zeus CAS Modules ⚡

The zeus CAS modules where slightly changed to improve frames, but in future patches ill add aditional changes to help improve frames while keeping/increasing their destructive effect.

## Low Poly Droids 🤖

I am aware that Low Ploy Droids dont have thermal signatures and will work on fixing that, but it is a low priority task. In all honestly just use the modified version the 212th has, I dont have access to the model so im not gonna make the few textures I have go through a painful process of textuing without a model. The UV is kind of garbo 😢.

## Stretcher 💉

The scripts related to the stretcher have been improved and to prevent the stretcher from crashing server when it is inside a trench, the script will look for a suitable location within 5 meter radius and deploy it 1 meters above the player.

## Factions 🎖️

The current system for factions (only effects zeus and eden) is workable for now,but I am a little bit uncomfortable with the layout of certain items so I will do some smol tweaks later on.

## Other 🤷

1. The marid has a dark skin, it was hidden before lol.
2. The AV-19 (AV-7 with Vanilla arty weapons, same as HOTs) is actualy spawnable lol.
3. Every aircraft, has color changeable HUDS. Self interact and you will see the option (or it might be just normal ACE interact, I forget lol. Windows key).

---

## Additions/Other

Below are the additions that dont fall under mod rework.

## Prototypes

The Prototypes have some results. At this current time there isnt really anything worth saying about them ,other then that there is a smol group of people that will be helping out with this task. I will release more information later on. So for now I removed them.

## Jumppack 🦘

Jumppack mod is doing well, ~~so well infact it might be in soon OwO.~~ Its in lol.

## For other mod devs 💻

Now if you edit any portion of 501st Aux mod with your mod or depend on certain addons or edit any vehicles, those will all change. Firstly here are all the CfgPatches

```cpp
"RD501_patch_main",

"RD501_patch_particle_effects",
"RD501_patch_Airborne_Helmet_Model",
"RD501_patch_VenatorMK2",

"RD501_patch_weapons",
"RD501_patch_jumppack",
"RD501_patch_helmets",
"RD501_patch_vehicle_weapons",
"RD501_patch_stretcher_model",

"RD501_patch_units",
"RD501_patch_vehicles",
"RD501_patch_zeus",
"RD501_patch_low_poly_droid_models",
"RD501_patch_stretcher",

"RD501_patch_low_poly_droids_config",

"RD501_patch_legacy_classnames"
```

Take note of how they are spaced out, for example 

```cpp
"RD501_patch_particle_effects",
"RD501_patch_Airborne_Helmet_Model",
"RD501_patch_VenatorMK2"
```

are all loaded before any of these are.

```cpp
"RD501_patch_weapons",
"RD501_patch_jumppack",
"RD501_patch_helmets",
"RD501_patch_vehicle_weapons",
"RD501_patch_stretcher_model"
```

Almost everyhing starts with `RD501` in configs and scripts, with a few exceptions such as B2 handgun or MTT.

### Legacy Classnames

I tried my best to keep old classnames in the mod so as to not casue any issues, but I am only 1 person so there is a chance I missed stuff. If so just tell me and I will see what I can do. But with Arma's latest update shortly after Contact DLC it helps reduce the impact of missing classnames since the arsenal will load it still.

As for the classnames I added, here is a list of them,you can find these under the `RD501_Leagacy_Classnames.pbo`. CfgPatches classnames are seperated out in their own folders as with legacy helmet classnames. Everything else should be in `RD501_Leagacy_Classnames/config`.

All legacy helmets are one of the vanilla arma 3 helmets with this reskin
![yeet][legacy_helm]


Here are some notable classnames that I think are most relevant

`laat_mk3` has become `RD501_LAAT_Mk3` and inherits from it.  
`O_SWOP_AAT_1_RD501` has become `RD501_AAT_Medium_MkII` and inherits from it.  
`SWOP_DC15ABlasterRifle_RD501` has become `RD501_DC_15a`  
`SWOP_DC15AGL_RD501` has become `RD501_DC_15a_gl`  
`SWOP_DC15ABlasterRifle_mod1_RD501` has become `RD501_DC_15a_LE`  
`SWOP_DC15ABlasterRifle_mod0_RD501` has become `RD501_DC_15a_mod_0`
`SWOP_DC17Pistol_RD501`  has become `RD501_DC_17`  

**Note** that these weapons have been replaced by the vanilla MX rifle and `scope=0`.

### Arsenal Loadouts

Assuming that you dont have VANA on, the arsenal will show greyed out kits. You may or may not be able to load them. If you hover over you will see this.

![yeet][arse_meme]

You se how it says `SWOP_dc15xBlastewrRifle_RD501_Mag`? Yea thats a classname that doesnt exist, and that may or may not make it so you can load your kit. If you cant load it send me, Namenai, a screenshot or the name of that item so I can make so your kit is loadable.

### Keys

I added keys again. wowe.

## Helmets ⛑️

### Aviation Helmets

1. CX-X Crashkun I mean Trashkun I mean Trashpanda I mean **CX-X Casskun** OwO
2. CX-X Arc Crash a lot I mean Yellow I mean Red I mean **CX-X Orange**

### Infantry Helmets

1. CP Khahortkne I mean **CP Courtney**
2. A metric shit ton made by Sam, plz say thank you to Sam. Do it or you have big smelly forever.

### AB Helmets

1. A shitton, blame lava for texture dump 😥
2. Purge trooper by CT Nut I mean CT Calo. Help by CT Ranger for glow.
3. CP Tuffs

## Clousing Remarks

This update is huge, maybe not in terms of content, but in terms of how the mod is made. As such I expect many bugs/kits not loading. So if thats the case please tell me, I cant fix what I dont know.
