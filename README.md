# 2Take1Script

The offical continued version of the 2Take1Script, a script made by [**haekkzer**](https://github.com/haekkzer/) who abandoned it and allowed me to take over

#### I removed the code from the github repo because people apparently dont have enough IQ to go to [**releases**](https://github.com/DemonKiya/2Take1Script-Revive/releases) and instead download the code directly which causes issues..

> Big Thanks Proddy and haekkzer himself who teached me some stuff about lua and helped me with issues!


### Table of Contents

[**Setup**](#setup)  
[**Features List**](#features-list)  
[**Customize the Script**](#customize-the-script)  
[**Known Issues**](#known-issues)  
[**Common Questions**](#common-questions)  
[**Changelog**](#changelog)

## Setup

Download the latest script release from this git-repo [**here**](https://github.com/DemonKiya/2Take1Script-Revive/releases). The script comes in a `2Take1Script.zip` file.

Extract the `.zip` file in the `scripts` folder from the menu (see the [**Scripts Guide**](https://gta.2take1.menu/features/local/scripts) for further details).
If done right, your `scripts` folder should contain:

- `2Take1Script.lua` (main script)
- `2Take1Script\` (folder with additional assets)

Once all the above is done, you can straight go to [**Scripts**](https://gta.2take1.menu/features/local/scripts) and select **2Take1Script.lua**.

If you have a problem loading this script, have a look [**here**](#common-questions).

## Features List

### Online Players

- Add to Fake Friends (with different options enabled)
- Unmark Modder
- Waypoint Player
- TP to Player
- Vehicle Options
  - Remote Controll Vehicle
  - Vehicle Kick (Quick/Gentle)
  - Trap in Vehicle (Set on Fire/Drown Underwater)
  - Teleport Player Vehicle (To Me/Underground/Ocean/Custom Coords)
  - Repair Vehicle
  - Vehicle Godmode (Give and Remove)
  - Modify Speed (0-500)
  - Apply Random Force
- Griefing Options
  - Radiation Lags
  - Face Fuck
  - Ragdoll Player (v1/v2)
  - Falling Asteroids
  - Delete Asteroids
  - Trap in Stunt Tube (Visible/Invisible)
  - Trap in Cage (Visible/Invisible)
- Attach Objects
  - Attach Entity from Aim
  - Clear Entities
  - Custom Attachments
- Log Events
  - Log Script Events
  - Reset Script Event Log
  - Log Net Events
  - Reset Net Event Log
- Script-Events
  - Custom Script Events
    - Enter Custom Script Event with Parameters
    - Send Script Events from a Custom presaved list
  - Give Bounty (Custom Input, Anonymous or Named)
  - Force to Island
  - Force to Mission (Several Missions Selectable)
  - CEO Options (Demiss/Terminate/Ban)
  - Passive Mode (Block/Unblock)
- Send PED Assassins
  - Attack Continuously
  - Godemode Assassins
  - Amount of Assassins (1-30)
  - Clear PEDs
  - Send Assassins (Custom Input)
  - Send Assassins from a custom list
- SMS Spam
  - Spam Delay
  - Custom SMS input
  - Send their SCID & IP
  - Send SMS from a custom presaved list
- Malicious
  - Basic Kick
  - Basic Crash
  - Entity Spam (PEDs/Vehicles)
    - Amount of Entites
    - Enable Automatic Cleanup
    - Delete Entities
    - Spam Entities (Custom Input)
    - Spam Entities (Presets)
  - Big Dick Crash
  - World Object Crashes (1-2)
  - Invalid Ped Crashes (1-3)

### Player Options

- Random Clothes
- Force Police Outfit
- Health Modifier
  - Fill Health
  - Quick Regeneration
  - Set Health (Input)
  - Unlimited Health regeneration
  - Revert health after disabling Health regeneration
  - Undead OTR
- Ragdoll Self
- Ragdoll Self (Loop)
- Aim Protection
  - Enable Aim Protection
  - Anonymous Punishment
  - Freeze
  - Ragdoll
  - Set on Fire
  - Explode
  - Remove Weapon
  - Electrocute
  - Kick
  - Crash
- Bodyguards
  - Godmode Bodyguards
  - Add Map Marker for Bodygaurds
  - Bodyguards Health (100-1000000)
  - Bodyguard Type (Presets)
  - Primary Weapon (Presets)
  - Secondary Weapon (Presets)
  - Max Distance to Player
  - Formation
  - Amount of Bodyguards (1-7)
  - Enable Bodyguards

### Vehicle Options

- Personal Vehicle
  - Teleport Personal Vehicle to me
  - Teleport Personal Vehicle to me and drive
  - Drive Personal Vehicle
  - Teleport to Personal Vehicle
- Always apply Vehicle Mods
- Vehicle Colors
  - Set Speed in Milliseconds
  - Random Colors
    - Random Primary
    - Random Secondary
    - Random Pearlescent
    - Random Neon Lights
    - Random Smoke
    - Random Xenon
  - Rainbow Colors
    - Rainbow Primary
    - Rainbow Secondary
    - Rainbow Pearlescent
    - Rainbow Neon Lights
    - Rainbow Smoke
    - Rainbow Xenon
  - Synced Colors (Random/Rainbow/Smooth Rainbow)
  - 100% Black
  - 100% Black-Toggle
  - Fade Black-Red
- Explosive Beam on Horn
  - Enable Beam on Horn
  - Select Explosion
  - Select Explosion 2
  - Select Scattering
  - Select Min Range
  - Select Max Range
  - Enable Horn for Player
- Set Heli Blades Speed 0-100%
- Boost Vehicle
- License Plate Speedometer (MPH/KMH)
- No collision
- Auto Repair Vehicle
- Swap Vehicle Seat
- Delete Current Vehicle
- Custom Vehicles
  - Moveable Robot
    - Enable Robot
    - Controllable Blasts
    - Moveable Legs
    - Collision
    - Rocket Propulsion (Visual)
    - Equip Miniguns on hands
    - Drive Robot
    - Self Destruction
  - Custom Vehicles
    - Preview Custom Vehicles
    - Delete Custom Vehicles
    - Spawn a Custom Vehicle from a presaved list
  - Options
    - Spawn in Custom Vehicle
    - Use Own Vehicle for Custom ones
    - Godmode on Custom Vehicles
    - Disable Moveable Robot Tampa Notify

### Animal Model Changer

  - Ground Animals
  - Water Animals
  - Flying Animals
  - Standard Models
  - Safe Model Change
  - Revert back Outfit
  - Fix endless loading Screen

### Lobby

- Block Areas with Objects
  - Teleport to Block Location
  - Block LSCs
  - Casino
  - Maze Bank
- Griefing
  - Blame Player for Explosion Kills (ID)
  - Set Explosions Invisible
  - Set Explosions Silent
  - Explode Lobby (Explosion Type Input)
  - Explode Lobby
  - Set Lobby on Fire
  - Orbital Cannon Spam
  - Water Hydrant Spam
  - Freeze Lobby
- Communication
  - Chat-Commands
    - Enable Chat-Commands (Friends/Everyone)
    - Delete Vehicles from `!lag`
    - `!explode <playername>`
    - `!explodeall` \[SU\]
    - `!kick <playername>`
    - `!kickall` \[SU\]
    - `!crash <playername>`   \[SU\]
    - `!crashall` \[SU\]
    - `!lag <playername>`
    - `!trap <playername>`
    - `!tp <playername>`   \[SU\]
    - `!clearwanted` \[NOT SU\]
    - `!vehicle <name>`
    - `!bigpp <playername>`
    - `!bigppall`   \[SU\]
    - `!vehiclegod <on/off>`
    - `!weaponsall`
  - Chat Spam
    - Spam Delay
    - Chat Spam (Input)
    - Echo Chat X Times (1-10)
  - SMS Spam
    - Spam Delay
    - SMS Spam (Input)
    - Send their SCID & IP
    - SMS Spam (Presets)
- Vehicles
  - Vehicle Blacklist
    - Block Vehicles
    - Activate Block Vehicles
    - Select from currently 16 blockable Vehicles
  - Vehicle Kick (Quick/Gentle)
  - Disable Control from near Vehicles
  - Modify Vehicle Speeds (-500 - 1000)
  - Reset Modifies
  - Include Self & Friends
  - Overwrite default Speedlimit
- Script Events
  - Custom Script Events
    - Enter Custom Script Event with Parameters
    - Send Script Events from a Custom presaved list
  - Bounty
    - Set Bounty after Death Value (0 - 10000$)
    - Give Bounty after Death Toggle (Anonymous or Named)
    - Give Bounty (Custom Input, Anonymous or Named)
  - Force to Island
  - Force to Mission (Several Missions Selectable)
  - CEO Options (Demiss/Terminate/Ban)
  - Passive Mode (Block/Unblock)
- Miscellaneous
  - Laser Beam Explode Waypoint
  - Random Explosions (selectable explosion type)
  - Shake Cam
  - Kill nearby PEDs
  - Notify Script Host Migrations
  - Notify Session Host Migrations
- Malicious
  - Karma every Script Event
  - Force Host
  - Punish Money Beggers
  - Punish Russian Speakers (Kick/Crash/Explode)
  - Geo-Block China
  - Kick Session
  - Crash Session (1-2)
  - Fix loading screen after Crash
- Player History
    - Store info in each Lobby subcategory
      - Lobby info
        - Shows number of logged Players
        - Hide Lobby from History
      - Players
        - NAME / Copy
        - SCID / Copy
        - IP / Copy
        - PlayerID
        - First Seen
        - Add to Blacklist
        - Add to Remember Modder
        - Copy Outfit
        - Is `<name>` in this lobby?
        - Were they a modder?

### Weapon Options

- Load Weapons
  - Flamethrower
    - Select Scale
    - Normal
    - Green
  - Shoot Objects
    - Enable Object Shoot
    - Delete Objects
    - Select Objects from a list
  - Delete Gun
  - Kick Gun
  - Model Gun
    - Standard Model Gun (PEDs)
    - Add Objects and Vehicles to Model Gun
  - Rapid Fire

### PTFX

- New years eve
- Sparkling Ass
- Sparkling Tires
- Smoke Area
- Fire Circle
- Fire Fart
- Fire Ass

### Modder Detection

- Remember every Modder
- Unmark Friends
- Mark all as Modders
- UN-Mark all as Modders
- Modder Detections
  - Max Speed Bypass
  - Illegal Name
  - Modded SCID
  - Modded Net-Events
  - Explosion based blame killing
  - Modded Script Event
  - Profanity Filter Bypass

### Miscellaneous
- Teleport High in Air
- Drive/Walk on the Ocean
- Drive/Walk this Height
- Weird Entity
- Real Time (Clientside)
- Auto Teleport to Waypoint
- Auto-Hostkick-Yourself
- Fake Ban Screen
- Stats
  - Reset Orbital-Cannon Cooldown
  - Disable Orbital-Cannon Cooldown
  - Fill Snacks and Armor
  - Set KD(Kills/Deaths)
  - Unlock Fast-Run Ability
  - Casino Heist
    - Teleport to Boards
    - Reset Heist
    - Quickstart Random
    - Quickstart Highest Payout
    - Manual Mode
      - Reset last Approach
      - Silent, BigCon, Aggressive
      - Hard, Difficulty, Approach
      - Money, Gold, Art, Diamond
      - Unlock Points of Interests
      - Unlock Access Points
      - Confirm First Board
      - Crew-Member-Weapon, Payout
      - Crew-Member-Driver, Payout
      - Crew-Member-Hacker, Payout
      - Weapon Variation
      - Vehicle Variation
      - Remove Duggan Heavy Gurds
      - Equip Heavy Armor
      - Scan Card Level
      - Mask Variation
      - Confirm Second Board

### Utility

- Delete Custom Outfits
- Delete Custom Vehicles
- Gameplay Clear Area
- Clear Area
  - Clear Distance
  - Clear Area of Cops
  - Clear Area of PEDs
  - Clear Area of Vehicles
  - Clear Area of Objects
  - Clear Everything
- Get Current Coords
- Leave-Session
- Delete Entity From Aim
- Get input Hash key
- Print Info from Entity @Aim to File
- Console (requires lua debug console)
  - Print 2T1Script log to console
  - Print Chat log to console
  - Print joining Players to console
  - Print leaving Players to console
- Logs
  - Log Modder Flags
  - Log Chat
  - Log Players
  - Log Console output
  - Enable 2T1Script logs
  - Cleanup
    - Clear All 2T1Script logs
    - Clear 2Take1Menu.log
    - Clear 2Take1Prep.log
    - Clear net_events.log
    - Clear notification.log
    - Clear player.log
    - Clear script_event.log
    - Clear All Menu Logs

### Options

- Hotkey Settings
  - Enable Hotkeys
  - Hotkey Notifications
  - Create Hotkeys.ini
  - Reload Hotkeys.ini
  - Print active Hotkeys
- Exclude Friends from Harmful Lobby Events
- Attached Entitys No Collision
- Disable Player-History
- 2Take1Script Parent
- Save Configuration

## Customize the Script

In order to customize the script, you have to edit the `2Take1Script\Data\EXTData.lua` file.

Although any text editor will do the work, I'd recommend a specialized code editor, such as **Notepad++**, **Visual Studio Code**, **Atom** or **Sublime Text**.

If you add something to a variable, set it to the last entry.

Here's an example:

```lua
-- This is RIGHT
local array = {
    {"Entry X", 10},
    {"Entry Y", 40},
    {"New Entry", -1},
}

-- This is WRONG
local array = {
    {"Entry X", 10},
    {"New Entry", -1},
    {"Entry Y", 40},
}
```

### Custom Script Events

Edit the `custom_script_events` global variable.

```lua
custom_script_events = {
    {"Custom Script Event 1", {
        {0xffffffff, {0, 0, 0}},
        {0xffffffff, {0, 0, 0}},
        {0xffffffff, {}},
    } },
    {"Custom Script Event 2", {
        {0xaaaaaaaa, {1, -1}},
        {0xffffffff, {0, 0, 0}},
    } },
}
```

### PED Assassins

Edit the `ped_assassins` global variable. If you dont provide a weapon hash, the peds weapon will be a Combat MG Mk II

```lua
ped_assassins = {
--  {"Attacker Name", ped_Hash, ped_Type, weapon_Hash(optional)},
    {"Cop", 0x5E3DA4A4, 6, 0x1D073A89},
    {"FIB", 0x5CDEF405, 6, 0x2BE6766B},
    {"Juggernaut", 0x90EF5134, 4, 0x42BF8A85},
    {"Bigfoot", 0x61D4C771, 28},
}
```

### Shoot Objects

Edit the `shoot_entitys` global variable.

```lua
shoot_entitys = {
--  {"Name", Hash, enabled by default},
    {'Boat', -1685705098, false},
    {'Bumper_Car', -77393630, false},
}
```

### Custom Attachments

Edit the `custom_attachments` global variable.

Each attachment can be made of many entities; you only have to add more entity identifiers.

```lua
custom_attachments = {
--    {"Name", {
--      {hash, bone_ID, {pos X, Y, Z}, {rot X, Y, Z}, bool_Invisible},
--      }, },
    {"DEMI-GOD - Light", {
        {148511758, 0, {0, 0, 0}, {0, 0, 0}, true},
        }, },
    {"DEMI-GOD - Heavy", {
        {148511758, 0, {0, 0, 0}, {0, 0, 0}, true},
        {3291218330, 0, {0, 0, -3.5}, {0, 90, 0}, true},
        {3291218330, 0, {0, 0, 0}, {0, 90, 0}, true},
        {3291218330, 0, {0, 0, 3.5}, {0, 90, 0}, true},
        }, },
    {"Cat Cap", {
        {0x573201B8, 119, {0, -0.075, 0.3}, {0, 0, 0}},
        }, },
}
```

The third example, "Cat Cap", uses a **ped hash**.

### New Custom Vehicles

Edit the `custom_vehicles` global variable.

This is the most complicated part of the Lua, but let's take it step by step.

1. The first line contains all **vehicle/object hashes** you want to use for the custom vehicle.
2. The next lines will define how each vehicle/object will be placed in the custom vehicle. You have to repeat this line for every hash you defined above. Keep in mind that the first of the hashes will define the **starting vehicle**.

- `hash`  
  This is the hash to which the next parameters will be applied.
- `{pos X, Y, Z}`  
  Set the offset of the entity.
- `{rot X, Y, Z}`  
  Set the rotation of the entity.
- `{primary_Color, secondary_Color, pearlescent, wheel, window}`  
  If the entity is a vehicle, set the primary/secondary/pearlescent/wheel color (all HEX RGB) and the window tint (0 to 3).
- `bool_Invisible`  
  Set this to `true` to render the entity invisible.
- `int_SpawnHeight`  
  If you have a plane as a starting vehicle, this value will let you spawn it at a certain amount of meters above the current location.
- `int_BoneIndex`  
  Set a boneindex if you want to attach something, for example, to the wheels.
- `int_AttachToEntity`  
  By default, everything will be attached to the first (starting) vehicle. To change that, just set it to the line number defining the vehicle where it should be attached.
- `ped_Hash`  
  To get the engine of a helicopter/plane running, you can set here a ped hash. The ped will be spawned into the vehicle, and the doors will be locked after it.
- `bool_NoCollision`  
  Set it to `true` to disable the collision for this entity.
- `int_Offset`  
  Defines how many meters away the entity should be spawned in front of you (especially for the preview).
- `int_OffsetZPreview`  
  Defines the height of the vehicle during the preview.
- `int_Alpha`  
  Some vehicles will glitch put if you render them invisible. Instead, set the Alpha to `0`.

The position/rotation *should* always be `nil` for the starting vehicle.

Setting some value to `nil` will set the default setting for it.  
For example, the color for each vehicle will be randomly selected.

Setting the starting vehicle's hash to `0` will check if you're in a vehicle and if the "Use own Vehicle" option is enabled.  
If that's the case, your current vehicle will become the "base", on which the rest of the entities will be attached.

```lua
custom_vehicles = {
--  {"Name", {
--      {hash1, hash2, hash3, ...}
--      {hash, {pos X, Y, Z}, {rot X, Y, Z}, {primary_Color, secondary_Color, pearlescent, wheel, window}, bool_Invisible, int_SpawnHeight, int_BoneIndex, int_AttachToEntity, ped_Hash, bool_NoCollision, int_Offset, int_OffsetZPreview, int_Alpha},
--      }, },
    {"WarMachine", {
        {0x9dae1398, 1030400667, 0x2F03547B, 2971578861, 3871829598, 3229200997, 0x187D938D, 782665360},
        {0x9dae1398, nil, nil, {0, 0, 0, 0, 1}, nil, nil, nil, nil, nil, nil, 15},
        {1030400667, {0, -4, 0}, nil, {0, 0, 0, 0, 1}},
        {0x2F03547B, {0, -8, 4}, {-90, 0, 0}, {0, 0, 0, 0, 1}, true, nil, nil, nil, 0x97F5FE8D, true},
        {2971578861, {-0.3, -0.6, 9.8}, {-90, 0, 0}, nil, nil, nil, 16, 3},
        }, },
    {"Attach Ramp", {
        {3233397978},
        {0},
        {3233397978, {0, 4.5, 0.25}, {0, 0, 180}},
        }, },
}
```

### Vehicle Spam

Edit the `vehicle_spam` global variable.

```lua
vehicle_spam = {
--  {"Name", Hash},
    {"Cargoplanes", 0x15F27762},
    {"Volatols", 0x1AAD0DED},
}
```

### Ped Spam

Edit the `ped_spam` global variable.

```lua
vehicle_spam = {
--  {"Name", Hash},
    {'Amanda', 0x6D1E15F7},
	  {'Prologue Driver', 0x855E36A3},
}
```

### SMS List

Edit the `sms_texts` global variable.

```lua
sms_texts = {
--  "Message 1", "Message 2", "Message 3", "..."
    "Fucking bitch", "REKT", "NOOB", "GET ON MY LEVEL", "Send Nudes", "UR MOM GAY"
}
```

### Load Weapons

Edit the `weapons` global variable.

```lua
weapons = {
--  {weapon_Hash, attachment1_Hash, attachment2_Hash, attachment3_Hash, ...},
    {0x1B06D571, 0xD7391086},
    {0x22D8FE39, 0x249A17D5, 0x359B7AAE, 0xC304849A, 0x9B76C72C},
    {0xCB96392F, 0xEFBF25, 0x420FD713, 0x27077CCB},
}
```

## Known Issues

- After disabling **2Take1Script-Parent**, you have to reload the script.
- Loading the script after using `Reset State` may result in the script activating features on it own, this is a lua api bug and cannot be fixed by me. Reinjecting the menu will temporarly fix it.
- Too many **Custom Vehicles / PEDs / Objects** may cause issues! Just delete them after use.
- Some features won't work properly if the distance between you and the target is too high.
- When the script gets autoloaded (for example, with an `autoexec.lua`), the **Event Listeners** (Chat features, etc) might not work.
- Teleport to Waypoint sometimes will teleport you near a street.
- Enabling Vehicle Colors might wont apply, press the Feature a few times.
- Rapid Fire doesnt work with the guided rocket launcher.
- Attachments -> Clear Entities sometimes doesnt work

## Common Questions

> How do I add stuff?

- See [**Customize the Script**](#customize-the-script)

> How do I enter a Custom Vehicle?

- Enable **Spawn in Vehicle** under **Settings**.

> Does it work with other scripts?

- It should work - it has been tested with a few other scripts. But i dont officially support co-loads.

> Does it work after a GTA Update?

- Chances are very high for all **Script Event** features to break; everything else *should* be fine.

> Does it work after a 2T1 Update?

- Yes, under normal circumstances.

> How do I reset the script config?

- Delete the  `config.ini` file in the  `2Take1Script` folder.

> My game crashed when i load the script?

- Delete the  `2Take1Script.ini` file in the  `2Take1Script_Revive\Config` folder.

> I dont see the Script in the menu?

- Press "Refresh Scripts"

> The kick/Crash from the script did not work on a player?

- The Kick and Crash mostly only works on normal Players. Modder with a good Menu will most likely block it.

> I downloaded the new version, but i dont see the new features?

- Clear the cache of the Browser and make sure you deleted every old file.

> I dont see the Online-Player Features?

- They are not in Local -\> Script Features located. Go to the Online Tab and select a Player. Under Script Features you will see the Features.


## Changelog

see [**releases**](https://github.com/DemonKiya/2Take1Script-Revive/releases/)
