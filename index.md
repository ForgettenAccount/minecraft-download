# Minecraft PE Download
## Minecraft 1.18.2
## Changelog

## Fixes:

Fixed an issue that affected some large world saves on PlayStation, resulting in corrupted textures and loss of data, in some cases ([MCPE-149193](https://bugs.mojang.com/browse/MCPE-149193))

Interacting with certain containers will once again properly open the inventory screen ([MCPE-148531](https://bugs.mojang.com/browse/MCPE-148531))

Fixed issue where breaking blocks, opening chests, and entering portals would be delayed/not work when there are lots of mobs nearby ([MCPE-149214](https://bugs.mojang.com/browse/MCPE-149214))

Fixed some worlds not correctly replacing Bedrock blocks with Deepslate blocks after upgrading to 1.18 ([MCPE-149251](https://bugs.mojang.com/browse/MCPE-149251))

### Download
Download Minecraft 1.18.2 [here](https://mcpedl.org/uploads_files/09-12-2021/minecraft-1-18-2.apk)

## Minecraft 1.18.20.21 (Beta)
### Changelog

## Frog

Frogs now jump more frequently

Frog Eggs renamed to Frog Spawn

The time for Frog Spawn to hatch into Tadpoles has been increased

Tadpole hitbox is now larger

Frog Spawn has a new texture

Frogs in Meadow biomes are now of the temperate variant

## Animation Tweaks

Tweaked Frog's jump and tongue animations

Cleaned up the animation, entity and controller files

Changed water and swim animations from linear to smooth

# Non-Experimental Features and Bug Fixes

#### Create New World

The *Create New World*screen has been given a new design that is now available for some players. We would love to hear your feedback on it in [this post](http://aka.ms/MCCreateNewWorldUI)!

## Vanilla Parity

Worlds can now be created with 64-bit seeds (-9223372036854775808 to 9223372036854775807) and those can be copied between Bedrock and Java to produce the same world ([MCPE-144994](https://bugs.mojang.com/browse/MCPE-144994)) ([MCPE-148168](https://bugs.mojang.com/browse/MCPE-148168))

Non-numeric seed UI inputs now produce the same seeds as Java Edition

Player's arm no longer twitches while charging a bow ([MCPE-148486](https://bugs.mojang.com/browse/MCPE-148486))

Falling blocks have full-block hitbox again

Fixed an error where Journeymen Clerics would offer Glowstone Dust instead of Glowstone Blocks ([MCPE-57524](https://bugs.mojang.com/browse/MCPE-57524))

Untamed Wolves can now be leashed ([MCPE-82050](https://bugs.mojang.com/browse/MCPE-82050))

## Blocks

TNT blocks now correctly move in a random X/Z direction once lit

Fixed an issue with resource drops occasionally remaining black after breaking and placing a block quickly in its place

Top Snow no longer clips with the block beneath when falling

## Commands

Added the "hasitem" filter for target selector of entities. This allows the player to target entities based on the items that have in their inventory or are wearing

## Gameplay

Fixed Fangs from the Illager spells not being spawnable in blocks with no bounding boxes

Water and Lava Buckets can now be used on underwater blocks cohabitating with water, such as Light Blocks or Big Dripleaves ([MCPE-148392](https://bugs.mojang.com/browse/MCPE-148392))

Players in Visitor Mode can no longer break Paintings and Minecarts ([MCPE-132869](https://bugs.mojang.com/browse/MCPE-132869))

Teleporting vertically beyond the visibility distance now loads the terrain correctly ([MCPE-150021](https://bugs.mojang.com/browse/MCPE-150021))

Improved accuracy of damage calculations

Fixed an issue where interacting with the Bell while holding a chargeable item would not continuously ring it ([MCPE-56968](https://bugs.mojang.com/browse/MCPE-56968))

Fixed a bug where the player could switch to gliding when riding in certain scenarios ([MCPE-147904](https://bugs.mojang.com/browse/MCPE-147904))

## Mobs

Mobs are now able to path over Azalea blocks ([MCPE-129373](https://bugs.mojang.com/browse/MCPE-129373))

Mobs are now able to path over Dripleaf blocks and properly pathfind on top of them, when not fully tilted 

Mobs are now able to path over Pointed Dripstone blocks and properly pathfind on top of them ([MCPE-133270](https://bugs.mojang.com/browse/MCPE-133270))

Mobs can now move properly on top of solid partial blocks, like Bells, Brewing Stands, and Enchanting Tables

Mobs can now jump from high enough solid partial blocks to full ones at a higher position 

Mobs can now jump over fences if they are standing on an adjacent slab or on another block high enough

Mobs can now move through less than half-block tall Top Snow even when the ceiling, if any, is as tall as the mobs themselves ([MCPE-148355](https://bugs.mojang.com/browse/MCPE-148355))

Mobs can now move through Coral and Coral Fans, as they do not consider them as solid obstacles anymore ([MCPE-128687](https://bugs.mojang.com/browse/MCPE-128687))

Fixed an issue where players could not access a Villager's trades while holding a spawn egg ([MCPE-76153](https://bugs.mojang.com/browse/MCPE-76153))

Fixed an issue where Witches spawned during Village raids could despawn during the raid ([MCPE-149883](https://bugs.mojang.com/browse/MCPE-149883))

Cod, Salmon, Pufferfish, Tropical Fish, and Dolphins once again spawn in deep variants of ocean biomes ([MCPE-150191](https://bugs.mojang.com/browse/MCPE-150191))

## Stability and Performance

Fixed a crash that could occur upon leaving the Zooming menu in the Dressing Room

## User Interface

Default tabs changed to "Craftable" on left side and to "Crafting" on right side of the Pocket UI inventory screen

Removed the question mark button on the Pocket UI inventory screen

Items requiring 3x3 recipes are no longer shown when the Crafting Table is not used

Players can now use auto-move to take off or equip armor in Crafting Table's menu while in Pocket UI ([MCPE-148970](https://bugs.mojang.com/browse/MCPE-148970))

Updated generic controller face button icons on mobile

Control + Backspace will now erase the whole word before the caret

Control + Delete will now erase the whole word after the caret

Control + Left Arrow will now move the caret to the beginning of the word before the caret

Control + Right Arrow will now move the caret to the beginning of the next word after the caret

## Villagers

Updated Villager trade tables for Armorer, Cleric, Fisherman, Shepherd, Toolsmith, and Weaponsmith to match Java Edition

Fixed an issue where Villagers did not hold the item they would trade when presented with Emeralds by the player ([MCPE-150303](https://bugs.mojang.com/browse/MCPE-150303))

Villagers no longer avoid Zombified Piglins ([MCPE-94102](https://bugs.mojang.com/browse/MCPE-94102))

Villagers no longer share Seeds and Beetroot Seeds

## Technical Updates

A world with "StorageVersion" 8 or lower will be increased to 9 and have its "RandomSeed" upgraded from using only the lower 32 bits of a 64-bit number to using the full 64-bit range while still representing the same number. This is only relevant for negative 32-bit seeds, which need a sign bit extension

## Additional Modding Capabilities Experiment/JavaScript APIs

Important! In this release and starting with this beta, we are removing the Additional Modding Capabilities experiment.  This experiment contained experimental JavaScript APIs launched in 2018 – and with this removal, JavaScript within worlds associated with this API will no longer function.  GameTest Framework – a separate JavaScript API – should not be impacted, nor should behavior pack/resource pack type add-ons more broadly. You can read more about this [via this article](https://aka.ms/mcamc).

## Commands

Added '/tickingarea' command preload overload

Entities must now be loaded for an area to be considered fully loaded and ticking

## Molang

Molang expressions inside animation scripts for actor resource definition (pre_animation and initialize) that contain capital letters are properly evaluated now with format_version 1.18.20 or higher

## User Interface

The loading progress screen now shows when loading ticking areas marked for preload

# Experimental Technical Updates

## Commands

Added a new '/volumearea ' command to create, remove, and list volumes in the world

## GameTest Framework

Please read the full changelog in [this post](https://feedback.minecraft.net/hc/en-us/articles/4423151445901-Minecraft-Beta-1-18-20-21-Xbox-Windows-Android-) . This page is too long.

*Updated January 27 2022*

### Download
Download Minecraft 1.18.20.21 Beta [here](https://mcpedl.org/uploads_files/27-01-2022/minecraft-1-18-20-21.apk)
