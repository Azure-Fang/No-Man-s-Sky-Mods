# No Man's Sky Mods
By "popular" request, I will upload mods that I create to this repository. Updates will be sporatic and will continue until either I lose interest in No Man's Sky (read as: when I'm dead) or Hello Games stops releasing updates (also, seemingly unlikely).

## No Ladder Latch (4.46)
Disables latching behavior on ladders of all kinds, requiring the player to hold the interact button to start climbing a ladder.

> GCCHARACTERGLOBALS.GLOBAL.MBIN

## No Terrain Edits (4.46)
Disables the "auto carve" behavior of base parts while building a base; placing base parts will allow them to clip into terrain rather than automatically editing the terrain, preventing unwanted edit creep and future automatic fill-in.

> METADATA\REALITY\TABLES\BASEBUILDINGOBJECTSTABLE.MBIN  
> METADATA\REALITY\TABLES\LEGACYBASEBUILDINGTABLE.MBIN

## Freighter Buildable Tech and NTE (4.45 - Steam Build 12190816)
By request, this mod reactivates a number of legacy freighter tech (such as hydroponics trays, medium refiners, etc.) as well as the Expedition 9 consoles (if you have them) on freighters and merges it with No Terrain Edits. SNAPPING IS NOT WORKING; I have not figured out yet how to re-enable snapping legacy tech like hydroponics trays or the Galactic Trade Terminal to legacy rooms, but they otherwise work.

> METADATA\REALITY\TABLES\BASEBUILDINGOBJECTSTABLE.MBIN  
> METADATA\REALITY\TABLES\LEGACYBASEBUILDINGTABLE.MBIN

## Anti-Profanity Filter (4.46)
There is a boolean switch inside the XML that controls the filter. It is fully hooked up, but not assigned to a menu option. This simply flits that switch, disaling the filter.

> GCDEBUGOPTIONS.GLOBAL.MBIN

## Dirt to Silicate (4.45 - Steam Build 12190816)
This mod adds a simple refiner recipe that converts the trade good "Dirt" into Silicate Powder at a ratio of 1:250. This ratio was selected based on comparative value and is in line with other Product-to-Material recipes (such as Aronium>Silver).

This mod is only localized to English (US) and English (UK)! It will still work in other languages, but will display "RECIPE_AZURE_DIRT" instead of a localized name. The localized recipe is called "Requested Operation: Silicate Refinement": if anybody wishes to have it localized into their native language, provide me with a translation and I will update accordingly.

> LANGUAGE\NMS_LOC4_ENGLISH.MBIN  
> LANGUAGE\NMS_LOC4_USENGLISH.MBIN  
> LANGUAGE\NMS_LOC7_ENGLISH.MBIN  
> LANGUAGE\NMS_LOC7_USENGLISH.MBIN  
> METADATA\REALITY\TABLES\NMS_REALITY_GCRECIPETABLE.MBIN

## Legacy Research (4.45 - Steam Build 12190816)
Restores the ability to research the legacy Wooden, Metal, and Concrete base parts that were deprecated as of Frontiers. Costs are as they were last seen when they were dummied out of the game.

> METADATA\REALITY\TABLES\UNLOCKABLEITEMTREES.MBIN

## Anomaly Detector Recipe (4.45 - Steam Build 12190816)
Adds a recipe, researchable at the Anomaly after researching Atlas Pass v2, to craft Anomaly Detectors. Requires the following materials:
* Walker Brain x1
* Tainted Metal x250
* Counterfeit Circuits x1

There is a cosmetic bug with the tree view when crafting this recipe: the three materials overlap, but are still interactible. As I am unable to isolate the cause, and the mod is still fully functional, I am releasing it as is until I can figure out how to pad tree cells.

> METADATA\REALITY\TABLES\NMS_REALITY_GCPRODUCTTABLE.MBIN  
> METADATA\REALITY\TABLES\UNLOCKABLEITEMTREES.MBIN

## Legacy Research and Anomaly Detector (4.45 - Steam Build 12190816)
As I am still unable to comprehend AMUMSS scripts, even with Jaggid Edje's assistance, this merges Legacy Research and Anomaly Detector Recipe.

> METADATA\REALITY\TABLES\NMS_REALITY_GCPRODUCTTABLE.MBIN  
> METADATA\REALITY\TABLES\UNLOCKABLEITEMTREES.MBIN


# Deprecated Mods
## MP Freighter
Hello Games has made it so that multiple player freighters can exist in a single system, but you can only see and interact with another freighter if you dismiss your own. Consequently, an option to dismiss your frieghter has been added. This is a fair compromise to prevent multiplayer refiner issues, so I will no longer maintain or distribute this mod.


# Pre-emptive FAQ
## What branch are you based on?
All mods I create are based on the experimental branch. However, I generally only update when Experimental and Public are at parity unless there's a critical update on experimental. Whatever the case, I will always provide the patch version next to the name on this page.

## When do you update mods?
All mod updates are dictated by updates to MBINCompiler and experimental patch swarms. In general, I update anywhere between a week and a month after the release of a major patch.

## Why not release on Nexus?
Because Nexus stripped mod authors of their rights and I will never support their business (yes, they are a business as much as they'd like you to believe otherwise) again.

## Why no AMUMSS scripts?
Because I'm Lua illiterate. Sorry.
