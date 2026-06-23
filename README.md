# CRX Pink Furry Handcuffs
<img width="1024" height="1024" alt="pink_furry_cuffs" src="https://github.com/user-attachments/assets/d251cde5-37d3-46cd-b6b6-986634e0b318" />
crx_furrycuffs!
A simple Furry Handcuffs script that allows players with the hand cuffs item in their inventory to cuff players for "playful" purposes!
You may NOT resell or reupload this content as your own!
Or I will find you!!! >:(

# crx_furrycuffs
FiveM hand cuff players with furry hand cuffs

# Dependencies
qb-core & es_extended

# Supported Invenvtories
ox_inventory & qb-inventory

# Steps on installing
* Drag and drop crx_furrycuffs into your resource folder
* Add paste the following in your server.cfg
* Ensure crx_furrycuffs
* Go to the README.md in crx_furry cuffs and add the item to your inventory system
* Supports ox_inventory & qb-inventory and ox_target & qb-target

# Configuration
```
Config = {}

-- Item Settings
Config.HandcuffItem = "pink_furry_cuffs"
Config.RequireItem = true

-- Time Settings (in milliseconds)
Config.CuffProcessTime = 3000   -- Time it takes to put cuffs ON
Config.UncuffProcessTime = 4000 -- Time it takes to take cuffs OFF

-- Prop Settings (Standard GTA 5 Model)
Config.PropModel = "p_cs_cuffs_02_s"
Config.PropOffsets = {
    bone = 57005, -- Right Hand
    pos = vector3(0.04, 0.06, 0.02),
    rot = vector3(-62.0, 0.62, 52.0)
}

-- Target Labels (Cleaned and explicitly separated)
Config.UseTarget = true 
Config.TargetCuffLabel = "Use Pink Furry Cuffs"
Config.TargetUncuffLabel = "Remove Pink Furry Cuffs"
Config.TargetIcon = "fas fa-lock" 

-- Animation Dictionaries
Config.AnimDict = "mp_arresting" 
Config.AnimName = "idle" -- Pose for the person CUFFED
Config.AnimFlag = 49

-- Animation for the ATTACKER (The one doing the cuffing)
Config.AttackerAnimDict = "mp_arresting"
Config.AttackerAnimName = "a_uncuff" 

-- Controls to Disable while cuffed
Config.DisabledControls = {
    24, 25, 37, 44, 45, 140, 141, 142, 257, 263, 289
}
```

# How to use #
Get the pink furry hand cuffs by adding them to a store and buying them or using a command to give the item to your self, then find a player and third eye them and cuff them with the pink furry handcuffs

* start the server
* ensure the resource has started in your console log
* boom, your done.

# Support
[I_AM_FULLYCRX Official Discord](https://discord.gg/6QchSKDY7j)
[Iron Justice Roleplay Official Discord](https://discord.gg/YJXZagSzh7)
