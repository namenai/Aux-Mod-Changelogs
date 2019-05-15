# Aerium Update Changelog

**501 R&D**   
_by:_ **CX-P Zatama** 🍀☘️🥔🥔🥔🥔   
_changelog by:_ **CX-D Namenai**🐉🐲

---
**Yavin Base controller** - "Luke, you switched off your targeting computer! What's wrong?"   
**Luke Skywalker** - "This missile spam is *fuckin* borin mate"

As the name suggests the main focus of this update was improving the gameplay in the skies, Star Wars dogfights took *obvious* inspiration from the white knuckle engagements of WWII, and with that in mind I have made various additions and changes in an attempt to capture the *ascetic* and *excitement* of space (Air) battles in the star wars universe. Here are the changes specific to that goal 🥔

---
# Table of Contents
For our lazy friends,here you go.

* [Vehicle Based](#vehicle-based)
    * [Vehicle Additions](#vehicle-additions)
    * [Vehicle Fixes](#vehicle-fixes)
* [Infantry Based (ARC, GI, Airborne)](#infantry-based)
    * [Vehicle Additions](#infantry-additions)
    * [Infantry Changes](#infantry-changes)
* [Aviation Based](#aviation-based)
    * [Functionality Additons](#functionality-additons)
    * [Aviation Items Removed](#aviation-items-removed)
    * [Aviation Changes](#aviation-changes)
    * [Aviation Weapon Additions](#aviation-weapon-additions)
    * [Aviation Munitions](#aviation-munitions)
    * [Script Functions](#script-functions)
* [Prototype](#prototype)
    * [Infantry Based Prototype](#Infantry-based-prototype)
* [Particle Effects](#particle-effects)
    
---
Lets start with the small stuff   
*Vroom Vroom Vroom* 🚗 🚚

- ###  Vehicle Based
    + ##### Vehicle Additions
        +   Republic H.O.T (Heavy ordinance tank) + CIS Variants 🥵
        +   Republic R.O.T (Rocket ordinance tank) + CIS Variants
        +   Hailfire Droid now contains approximately 75% more hail (Hella more weapons, like AA)
    + ##### Vehicle Fixes
        +  Issue preventing servers loading with 212th mod loaded
---
*Pew Pew Pew* 🔫

- ### Infantry Based
    + ##### Infantry Additions
        +  Republic L.I.T (Light Infantry Transport) 🔥 
            * Large infantry transport for moving multiple full squads  
    + ##### Infantry Changes
        +  Backpack Normilization
            + All Backpacks
                + Maximum Capacity increased to 600 (from 500) 
            + Demolition Backpack
                + Maximum Capacity decreased to 600 (from 700)
        +  AP Grenade
            + AP Grenades now carry a small explosive radious and should no longer be capable of penetrating multiple targets.     
        +  DC15 LE
            + Magazine Weight reduced by 50% 
        +  RPS6
            + Adjust recoil values  
---
Now the best changes for Aerium for last.
- ### Aviation Based
    + #### Functionality Additons
        + Targeting Computers 🎯
            + All combat aircraft now come equipped with an AI turret which greatly improves the effectiveness of laser weapons. These turrets are for AI use only, are limited in their rotation and zeus is able to delete the turret. There is also a new function mentioned above for players to do the same.
        + Missiles
            + A new range of missiles for all aircraft, balanced around vanilla values
        + Bombs
            + A host of ordinance with various features, balanced around vanilla values
        + Cannons
            + All aircraft in addition to the turret recieved an upgrade to their main guns, this is to make up for the lack of a turret on player controlled aircraft. The AI will use these guns in rare circumstances and with CAS modules, so watch out!
        + Bloodlust
            + All aircraft are now capable, and very willing, to engage infantry targets.
        + Damage Check
            + Hull integraty check added to all aircraft    
    + #### Aviation Items Removed
        + Missiles
            + Like, all of them, get good
        + Bombs
            + Yeeted them too. 💣
        + "Repulsor Full Stop" that stops by killing you 💀
            + Who even came up with this in the first place? 
    + #### Aviation Changes
        + All aircraft
            + Stability
                + All non clone wars era aircraft have had their mass adjusted to perform more reliably at speed.
            + Performance
                + Aircraft are no longer capable of exceeding the maximum altitude of the zeus camera.
                    + This is a **highly experimental** change, feedback is ***extremely*** important.Maximum thrust is at 1.7km and loses all thrust at 2km. The little bird flies higher
            + Loadout
                + All aircraft have had their weapon loadouts altered drastically
        + Delta 7A
            + Model changed to Delta 7B to fix mesh issues
        + Armor Templates
            + Armor has been normalised across all airframes
                +   Interceptor Class - 100 Armor 🛡️
                +   Fighter Class - 200 Armor 🛡️
                +   Bomber Class - 300 Armor 🛡️
                +   Transport + Hero Class(Mordhau grip mode ⚔️) - 600 Armor 🛡️
                +   **Armor is increased by 100 if the aircraft carries a shield generator in lore,however there are exceptions**
                +   BTW its Armor *NOT* Armour you weirdos 👌
        + CX-P Zatama 🥔
            + Now capable of enjoying the game  
        + CX-D Namenai 🐲
            + Can drop peoples frames faster 
    + #### Aviation Weapon Additions
        + Weapons & Vehicles
            + "Aircraft Laser Cannon" + CIS Variant
            + "Aircraft Laser Gun" + CIS Variant
            + "Swarm AA Launcher" + CIS Variant "CIS Swarm AA Launcher"
            + "Tyrant AA Launcher" + CIS Variant "CIS Tyrant AA Launcher"
            + "Oneger AA Battery" + CIS Variant "CIS B.E.A.R.D"
            + "Rayne Delivery System"
            + "Wynd Launcher System"
            + "Plasma Cannon"
            + "Warden Tank MK.2" - Thank you CS Royale for the great texture! 💚
            + "Razor Blade" Sidearm 
                + Model is the DC-15 SA, it features a 8 round mag, very slow rate of fire, very high recoil.
            + PS-22 Scatter Rifle
                + Shoots .22 Long Rifle rounds as a shotgun, Uses DP-23 model,10 round mag, very good at hitting fingers.
    + #### Aviation Munitions
        + "Aircraft Cannon Laser CIS"
        + "Aircraft Cannon Laser Rebellion"
        +   "Aircraft Cannon Laser Republic"
        +   "Aircraft Cannon Laser Imperial"
        +   "Aircraft Cannon Laser Ion"
        +   "Aircraft Gun Laser CIS"
        +   "Aircraft Gun Laser Rebellion"
        +   "Aircraft Gun Laser Republic"
        +   "Aircraft Gun Laser Imperial"
        +   "Aircraft Gun Laser Ion"
        +   "Plasma Cannon Shell"
        +   "Zephyr A2A"
        +   "Torrent AGM"
        +   "Hurricane UGM"
        +   "Flashfire LGM"
        +   "Spyker G2A"
        +   "Wasp G2A"
        +   "Thunderstorm CB"
        +   "Wrath PGB"
        +   "Ruin GB"
    + #### Script Functions
        + Towing function for warden tank 💖
        + Airlift function for LAAT/C (Usable on all vehicles)
        + "Disable Turret" Function for all applicable aircraft
        + A survivable crash function has been modified and re-enabled for the majority of player aircraft. **Any** abuse of this function will result in **disciplinery action** and me, Namenai, *literally scripting you out of existance*. 

---
*This is where the fun begins* 😀  
## Prototype
These are the prototype changes. Basicly they are changes that we the real mod boiz are playing around with. They are not ment to be used on any full scale offical capacity but rather to get peoples thoughts and feelings and get input on the changes. For example we have 2 prototypes: DC-15S Carbine and DC-15A Rifle prototypes. Now the reason for these changes is to expand the room in which each weapon can vary from each other. Right now its very difficult to make any weapon diffrent from one another due to the range of parameters availible. So the prototypes are ment to expanmd that range to give each gun a diffrent flavor. These are ofcourse ment for testing and may or may not be balanced. 🤣

There is a naming scheme to this. For example we have
```
(PROTOTYPE Class N) DC-15A
```
This means that this is a prototype of the DC-15A made by namenai, N for namenai holy shit, so if theres any issues/suggestions/toughts you would go talk to namenai directly. Class Z is for Zatama and Class R is for Rexi (RIP ⚰️). Ez PP ezy dont get it twisted now.
- ### Infantry Based Prototype
    - #### Prototype Class N DC-15A
        - Semi auto only, shoots every 0.6 seconds which means rate of fire is 100 rounds per minute
        - Hella kick, based of recoils from shotguns in UNSUNG but tuned up, blame flog 🤣
        - As such the damage of the one and only mag that it can use is way more then even the currnet LE's damage. 30 round mag aswell. 
        - x4 scope with the scope picture thing is the same as the LE's becuase the old one, while looking nice cause of its white accents, was shit cause the red dot was like 4 times bigger then a droid at close range.
        - Oh also has 100% accuracy, 0 dispersion, so if you miss its your fault.
    - #### Prototype Class N DC-15S
        - Literally 1000 rounds per minute
        - thats it

---
*What are frames* 🎞️
## Particle Effects

The most I will say is, go throw an explosive and see that refraction effect. Most explosives should have it.