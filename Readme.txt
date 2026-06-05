--
-- LevelRange :: Readme
-- Copyright (c) 2006 Philip Hughes (Bull3t) 
-- http://bull3t.blogspot.com
-- 

----------------------
Details
----------------------
Title: 	        LevelRange
Interface:      11200
Version:        2.3.0

Author:         Bull3t, Tenyar97, rado-boy, blehz, rafacc87, Diginfotek, Spartelfant, Dusk-92.
Addon Website:  https://github.com/Tenyar97/LevelRange-Turtle

Current Features:
 [*] Shows zone level ranges, diplomacy, raids and instances on World Map.
 [*] Has two slash commands for easily reloading the User Interface.


----------------------
Change Log
----------------------
2.3.0 - Update (Dusk-92)
 [*] New zones added for patch 1.18.1 (Moonwhisper Coast)
 [*] New dungeons added for patch 1.18.1 (Windhorn Canyon, Frostmane Hollow)
 [*] New raid added for patch 1.18.1 (Timbermaw Hold)

2.2.0 - Update (Spartelfant)
 [*] Added Portuguese translation by rafacc87.
 [*] Added German translation by rafacc87.
 [*] Added French translation by Diginfotek.
 [*] Added Chinese translation by rafacc87.
 [*] Rename dungeons and raids in spanish.
 [*] Restructure translation files.

2.1.0 - Update (Spartelfant)
 [*] Added Spanish translation by rafacc87.

2.0.8 - Update (Spartelfant)
 [*] Fixed location of Dragonmaw Retreat: I had listed it mistakenly as being in Grim Reaches, but it's located in Wetlands.

2.0.7 - Update (Spartelfant)
 [*] Fixed bug in workaround for game bug. I previously used string.match() which is not available in-game, but during testing I had another addon active that made this function available, which is why I did not catch this.

2.0.6 - Update (Spartelfant)
 [*] Added workaround for game bug that prevented the new Northwind zone from showing a tooltip: The game included a trailing space, so the actual zone name is 'Northwind '.

2.0.5 - Update (Spartelfant)
 [*] New zones added for patch 1.18 (Grim Reaches, Northwind, Balor)
 [*] New dungeons added for patch 1.18 (Stormwrought Ruins, Dragonmaw Retreat)
 [*] Fishing skill required for new zones not yet known, will be added some time after patch release

2.0.4 - Update (Spartelfant)
 [*] Bugfix: Variables to prevent unnecessary updates were never set which was causing unnecessary updates to be performed.
 [*] Bugfix: Added missing index for Fishing option which was causing it to not appear in the settings window.
 [*] Added colors to status messages when toggling options.
 [*] Cleaned up code: Converted stray tabs to spaces, removed trailing whitespace, fixed some indentation, reordered some lines, etc.
 [*] Cleaned up TOC file.
 [*] Added my name to list of authors.
 [*] Addon forked on GitHub by Spartelfant in order to fix some bugs.

2.0.3 - Update (blehz.)
 [*] Updated zones, dungeons and raids to Turtle WoW 1.17.1.

2.0.2 - Update (rado-boy)
 [*] Added togglable option to show fishing level requirement on tooltip.  Not all zones are complete currently.

2.0.1 - Update
 [*] Updated outdated refrences.
 [*] Improved localization.
 [*] Removed "The Lower Karazhan Halls", as it is not added yet.
 [*] Fixed bug where "Black Fathoms Deep" did not appear in Ashenvale's information box.

2.0.0 - Release
 [*] Ported to Turtle-Wow
  [*] Added Zone: Gillijim's Isle
  [*] Added Zone: Lapidis Isle
  [*] Added Zone: Tel'Abim
	
  [*] Added Dungeon: The Crescent Grove
  [*] Added Dungeon: Hateforge Quarry
  [*] Added Dungeon: The Karazhan Crypt
  [*] Added Dungeon: The Stormwind Vaults
  [*] Added Dungeon: Caverns of Time: The Black Morass
	
  [*] Added Raid: The Emerald Sanctum
  [*] Added Raid: Lower Karazhan Halls

1.2.0 - Update
 [*] Added the showing of raids and raid level ranges.
 [*] Added an options frame, you can now specify what you want on and off, access with "/lr" or "/levelrange".
 [*] Added myAddons support, LevelRange will now show in myAddons correctly.
 [*] Added a small help system.
 [*] Added ReloadUI shortcut slash commands, this shortcut is on many addons, and is very useful, reload the UI with "/rui" or "/reloadui".
 [*] Changed the way LevelRange shows instance level ranges.
 [*] Fixed a bug with FlightMap collision, if FlightMap is enabled, LevelRange will be shown on the right, instead of the left.

1.1.0 - Update
 [*] Added the showing of instances and instance level ranges.
 [*] Added slash commands, but currently they do nothing.

1.0.0 - Release
 [*] Public release version.
