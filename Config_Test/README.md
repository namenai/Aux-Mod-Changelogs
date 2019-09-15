# Ye old big test <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [Test](#test)
- [What you will learn from this](#what-you-will-learn-from-this)
- [Resources](#resources)
- [What to do](#what-to-do)

## Test

Your mission, *should you choose to accept*, is to make a vehicle weapon that can shoot at infantry, vehicles, air targets, and sea vehicles(we only care about the speedboat). Here are some properties of this weapon

1. Shoots bullets/tank shells/rounds.
2. Vehicle weapon, so you dont need to worry about model
3. For simplicity sake, add it to the Nemmera, under the tracked APC section. Its a vanilla vehicle the same that the wardens use for the warden tank.
4. try to keep things as vanilla as possible and use as many vanilla assets as you can.

## What you will learn from this

1. Making a mod in arma
2. Taking something from base game,and changing it.
3. Understanding how Arma does things, for better or for worse.

## Resources

Since you have PBO manager, Sublime text,VS code and Arma 3 tools installed, your gonna need these refernces since Arma 3 is a big game.

1. [This](https://forums.bohemia.net/forums/topic/191737-updated-all-in-one-config-dumps/?do=findComment&comment=3371924) is a file thats about 40mb, 1.3 million lines of code, and is all of the configs in Arma (with whatever mods this person has, which is just vanilla). Download this and open it with Sublime text since its better for big files. Think of this is a big table telling you how Arma defines stuff,like whats the rate of fire of a weapon, the ammo, sound and what not.

2. [Ammo reference](https://community.bistudio.com/wiki/CfgAmmo_Config_Reference),[Magazine reference](https://community.bistudio.com/wiki/CfgMagazines_Config_Reference),[Weapon reference](https://community.bistudio.com/wiki/CfgWeapons_Config_Reference),  [Targeting reference](https://community.bistudio.com/wiki/Arma_3_Targeting_config_reference) and [Vehicle refernce](https://community.bistudio.com/wiki/CfgVehicles_Config_Reference). The first three are the documentation on what properties ammo,mags, and weapons have. For example it tells you what variable relates to the damage value of a ammo, or what value means the magazine count or what value means rate of fire. The 4th link tells you what variables are used to determine how AI/weapons target stuff. The 5th is about vehicles so stuff like armor, what weapons a vehicle has and how many of each magazine. I know its a lot but just read it slowly and take your time.

## What to do

- So now heres a big question, how would you go about doing this? Well lets think about it and break it up in pieces. Whats a weapon that shoots at air targets? a weapon that targets vehicles? a weapon that targets infantry? a weapon that targets sea vehicles?

- The CSAT Tigris attacks air targets, the speedboat and cars/trucks/apc/ifv. But it doesnt attack tanks. Thats almost all the targets you need to be able to target.
So what weapon can attack tanks? Well any of the tank cannons can lol. So if you can figure out how the Tigris gun works and a tank cannon,you can figure out whats the difference and combine them together.

- So now we need to find out what gun the Tigris uses. Remember that 40mb file, the AIO config, we can use that. Search for `O_APC_Tracked_02_AA_F`. Thats the normal Tigris. If you scroll down and look for `class Turrets: Turrets` you will find all the turrets that are defined for the Tigris, we want the gun on the main turret.

- Now lets say the gun is called `XXXXX`, if you wanna find the gun search for `class XXXXX:`. That will give you the gun.

- Theres quite a bit of more stuff to do, but I dont wanna make this file 10 years long. Just get to me at one point and we can talk.
