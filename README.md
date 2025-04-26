BN5_Cheap_Trade_Chain mod
==============================

This is a mod for Mega Man Battle Network Legacy Collection Vol. 2 for Battle Network 5.

Battle Network 5 was infamous for making you give away PvP important chips with decent chip code to NPCs for no reason outside of completing chip library. The chips traded and order are as follows:

Slow Gauge * -> North Wind * -> Grab Revenge F -> V Doll T-> Anti Damage * -> Dark Invisible I

Only Slow Gauge * can be farmed and traded away. Dark Chips and Giga Class are always excluded from any chip trader. However, the four standard chips with that specific code, between those trade chain cannot be traded to another player or put in Chip Trader. This is because Legacy Collection has excluded them from the list, which doesn't happen in original GBA or DS. Because of that, players had to hard earn those chips from Oran Chip Trader Special and that can take thousands of attempts to even get a copy. Nonetheless, you can only have 2 copies of Anti Damage * as none of the chip/bug machine traders drop Anti Damage in this code. Completing the chain, means you lost your only second copy of Anti Damage * permanently because of this feature. To add salt to the wound, Dark Invisible can be obtained in * code from the Number Trader machine at Higsby when you start chapter 3. So doing all this trade chain in Chapter 5 onwards for Dark Invisible I is pointless, debilitating side quest.

This mod changes what chips required and preserve those chips from being taken so you can reserve those chips for PvP (if there is any). 
 
Features
--------
* Every trade that requires a Battle Chip to obtain a Navi Cust Program/Battle Chips/lotto number info are changed to Guard1 A.

* Guard1 A is a common early game chip that is easily obtainable in any version and by the time you actually reached these NPCs in Chapter 5, you may have dozens of them in your pack and don't even used it anymore when Guard1 * exist. Even if you don't have that many anymore, it is very easy to get it back.

* The quantity received for every chip outside of Anti Damage * has been increased to 4 instead of just 1.

* Anti Damage * is retained as 1 in the trade chain because of its situation not being tradeable with other players and you can't gain more through chip or bug trader machine. If there is a major update where we can trade those chips again, I'll update this mod to increase its quantity. Otherwise, it remained as it was by default. 

Potential Bug
-------------

* Completing the Trade Chain until Dark Invis I has a potential of deleting all copies of North Wind *, Grab Revenge F, V Doll T and Anti Damage * permanently from your pack if they're not equipped to any folder. This bug happens prior to this mod's existence and the cause has yet to be found. To be safe, do not obtain Dark Invis I at all. 

Installing
----------

Windows PC and Steam Deck

1. Download and install chaudloader: https://github.com/RockmanEXEZone/chaudloader/releases Version 1.0.0 or newer is required.

2. Launch Steam in Desktop Mode. Right-click the game in Steam, then click Properties → Local Files → Browse to open the game's install folder. Then open the "exe" folder, where you'll find MMBN_LC2.exe.

3. Copy the Cheap_Trade_Chain folder to the "mods" folder.

4. Launch the game as normal.


Version History
---------------

Ver. 1.0.0 - 26 April 2025

* Initial version.


Building
--------

Building is supported on Windows 10 & 11. First install the following prerequisites:

* Download TextPet v1.0.0 or newer from https://github.com/Prof9/TextPet/releases and copy it into the "tools" folder.

Then, run one of the following commands:

* make - Builds the mod files compatible with chaudloader.
* make clean - Removes all temporary files and build outputs.
* make install - Installs the previously built mod files into the mods folder for chaudloader.
* make uninstall - Removes the installed mod files from the mods folder for chaudloader.
