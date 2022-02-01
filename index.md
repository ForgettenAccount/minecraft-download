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

