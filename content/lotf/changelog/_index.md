---
title: "Changelog"
weight: 7
type: docs
description: >
  Update notes for Legends of the Frost.
---

## Release 2.1

> 07/01/2022

I hadn't planned to update LOTF again, but the recent SSE update made it necessary. This update was compiled with SSE 1.6.353.0 which is the latest version so please do not use the downgrade patcher.

#### Mod Changes

- Added Optional Round Farmhouse Posts
- Added Major Cities Mesh Overhaul
- Added 3D Whiterun Trellis
- Added 3D Riften Trellis and Roofs
- Added 3D Solitude Market Trellis
- Updated DynDOLOD to Alpha 60
- Updated SSE Display Tweaks to 0.5.8
- Updated DynDOLOD Resources Alpha 17
- Updated Assorted Mesh Fixes to 0.41.1
- Updated Flickering Meshes Fix to 1.8
- Updated Better Windhelm Ground Meshes to 1.3.3
- Installed the Majestic Mountains / Skyrim Mountainous patches from Flickering Meshes Fix separately
- Moved Skyrim Landscape and Water Fixes below the ESSENTIALS separator
- Set two meshes in SMIM that were conflicting with SLaWF to hidden
- Disabled physics damage via SSE Display Tweaks (new feature)
- Removed physics damage threshold command from the Autorun.txt (now covered by SSE Display Tweaks)
- Removed bigger sandboxing radius command from the Autorun.txt (has some unintentional side effects)
- Better Windhelm Ground Meshes now has priority, fixing a visual bug (thanks Shade088!)
- Fixed a minor visual glitch on the shore across from Solitude's harbor
- Fixed Slightly Better - Old People Consistency being disabled on the LOTF CC profile
- Restored LOTF's tweaked version of Minimal ENB for Obsidian Weathers thanks to Slim
- Reinstalled MO2 plugins that were lost after the update (deorder's, LOOT Preventifier)
- Disabled the Sort Plugins button in MO2 (another change lost after uppdating)

*Note that while I did update DynDOLOD, I did not regenerate LODs for this update.*

#### Website Changes

- **Installation:** Updated latest version number.

## Release 2.0.2

> 02/01/2022

Of course I forgot to update the SSE version shenanigans in the Installation instructions and probably caused quite a bit of headache because of that. LOTF 2.x requires the *latest* version of Skyrim SE installed in your Steam folder. Thanks to JanuarySnow for reminding me!

#### Website Changes

- **Installation:** Fixed a fairly critical oversight, clarified that latest SSE version is required for installing LOTF

## Release 2.0.1

> 01/01/2022

So the initial 2.0 release was unplayable, cool.

After fixing 2.0 and realising that I was still unable to compile, I found out that at some point I had yeeted my backup of the modified Minimal ENB for Obsidian Weathers that LOTF has been using alongside Wander. I ultimately just reinstalled the preset and applied the tweaks that I still remembered but it's probably not all of them. I honestly don't know. Either way, I recommend The Truth ENB and the only reason it's not the default preset is because it was taken off the Nexus.

#### Mod Changes

- Obsidian Weathers and related mods are now actually included
- Replaced texture BSAs in Stock Game folder with UPOT (Unofficial Performance Optimised Textures)
- Fixed an error in the WABBAJACK_IGNORE_FILES.txt that caused the entire Stock Game folder to be ignored
- Reinstalled Minimal ENB for Obsidian, some tweaks were probably lost

## Release 2.0

> 31/12/2021

- Support for **Obsidian Weathers and Seasons** as an alternative to Wander.
- Instructions for **swapping out** the ENB preset for Truth ENB **or disabling ENB** altogether.
- Inclusion of **Nemesis** as well as a stripped down XPMSSE for **Simple Dual Sheath**.
- Better water (**Realistic Water Two**), readable road signs (HD Road Signs), new grass overhaul (Enhanced Landscapes).
- New **Creation Club profile** with support for 14 Creations (so far).
- New **performance profile** with lighter INI settings and DynDOLOD setup (not compatible with CC profile).

LOTF 2.0 utilizes the "Best of both worlds" downgrade patcher in order to be able to stay on SKSE 2.0.20 for SSE 1.5.97.0 (pre-AE). This is because not all of LOTF's SKSE-dependent mods (25/38) were updated yet. With the "best of both worlds" patcher all game files other than the executable are from the latest AE version though, meaning all assets for new creations are present and AE content can be used.

**Removal of Immersive HUD:** Skyrim's UI is fairly unintrusive already, but the ability to disable the HUD still comes in handy for taking screenshots. iHUD unfortunately has some issues with the crosshair (it sometimes vanishes completely for me) so I decided to just replace it with Luca's version of fadingsignal's Hide UI. It completely disables the UI at the press of a button so it doesn't ruin a pretty screenshot.

#### How To Update

Before updating LOTF to 2.0 for an ongoing playthrough, please load your latest save and follow these instructions:

- In the **Immersive HUD** MCM, please uncheck **iHUD Active** to completely turn off iHUD.
- Make sure you are in an exterior location and open the **DynDOLOD** MCM.
- Uncheck **DynDOLOD is active** and wait for the confirmation box to pop up.
- Go into any interior cell and save, then quit the game.
- In Mod Organizer 2 under the **CRP & PATCHER OUTPUTS** separator, uncheck the **TexGen** and **DynDOLOD** outputs.
- Load your save, click **OK** to missing masters, and create a new manual save.

Now you can safely update LOTF through Wabbajack and continue your playthrough.

#### Legends of the Frost

- Added Spiders of Solstheim - Transparency Fix
- Added HD Road Signs 2K
- Added Weather of World
- Added Realistic Water Two
- Added Blacksmith Forge Water Fix - Realistic Water Two Patch
- Added Flickering Meshes Fix
- Added Shaders of Solstheim - Ash and Moss
- Added Snowy Windhelm Bridge
- Added Enhanced Landscapes - Grass Overhaul
- Added Tempered Racial Textures
- Added Slightly Better - Old People Consistency
- Added Nemesis Unlimited Behavior Engine
- Added Dynamic Animation Replacer
- Added XP32 Maximum Skeleton Special Extended
- Added Draw 2 - Dual Weapon Equip-Unequip Animations
- Added Simple Dual Sheath
- Updated Mod Organizer to 2.4.4
- Updated SSELODGen to Beta 85
- Updated DynDOLOD to Alpha 56
- Updated Cathedral Assets Optimizer to 5.3.8
- Updated SSE Display Tweaks to 0.5.6b
- Updated Weapons Armor Clothing and Clutter Fixes to 2.8
- Updated DynDOLOD Resources to Alpha 16
- Updated Assorted Mesh Fixes to 0.41
- Updated powerofthree's Tweaks to 1.4.1
- Updated Spell Perk Item Distributor to 5.2
- Updated Charge Dialogue Fix to 1.3
- Updated Simplicity of Snow to 0.5
- Removed Dlizzio's Mesh Fixes - Assorted Mesh Fixes Patch (overwritten)
- Removed Immersive HUD
- Removed Immersive HUD - Settings Loader
- Removed Immersive HUD - LOTF Preset
- Removed Relighting Skyrim - No Player Homes
- Removed Picta Series - Improved Sky Meshes
- Removed Cathedral Water Overhaul (replaced by RW2)
- Removed Volcanic Tundra - Heat Wave Effects (replaced by RW2)
- Removed Skyrim Flora Overhaul - Grass Only (replaced by EL Grass)
- Removed Security Overhaul SKSE - Lock Variations (out of scope for LOTF)
- Removed cleaned master files
- Installed XPMSSE version of Werewolf Claws Affect Spider Webs and moved it lower in the mod order
- Moved Ambiance plugin lower in the load order
- Moved Skyrim Realistic Overhaul BSAs below Project Clarity BSAs to overwrite
- Rebuilt most of the Project Clarity BSAs
- Fixed load screen blocker (DynDOLOD load screens should no longer appear)
- Hopefully (?) fixed two flickering lights in Honeyside (one remains)
- Disabled logging in Keyboard Shortcuts Fix
- Changed the ENB FPS display hotkey from F7 to F8
- Reinstalled SkyHUD without the Immersive HUD patch
- Reinstalled Majestic Mountains without the effect meshes
- Installed zEdit in the Tools folder for the SLaWF Remove Crop Ownership script
- Completely remove the crop ownership feature in Skyrim Landscape and Water Fixes
- Re-enabled faction stealing in powerofthree's Tweaks
- Included three custom presets with the CAO installation as requested
- Added an icon to the SKSE executable (installation instructions were updated accordingly)
- Resolved conflicts between new mods in the CRP
- Regenerated facegen for the main and CC profiles
- Generated Nemesis output
- Regenerated terrain LOD with SSELODGen Beta 85
- Regenerated tree and object LOD with DynDOLOD Beta 58

#### LOTF Wander ENB

The preset is a tweaked version of Minimal ENB for Obsidian 1.1 (now Yuevie's Minimal ENB).

- Incorporated RW2's recommended ENB water settings
- Removed some arbitrary tweaks in the ENB grass section
- Removed some arbitrary tweaks in the ENB particles section that made water in interiors at night unnaturally bright

#### Creation Club Profile

**Supported Creations:**

- Saints & Seducers
- Forgotten Seasons
- The Cause
- Divine Crusader
- Netch Leather Armor
- Chrysamere
- Alternate Armors - Daedric Mail
- Alternate Armors - Dwarven Mail
- Alternate Armors - Ebony Plate
- Alternate Armors - Elven Hunter
- Alternate Armors - Stalhrim Fur
- Alternate Armors - Steel Soldier
- Alternate Armors - Studded Dragonscale
- Rare Curios

**Additional Mods:**

- Added Cleaned and Upscaled Textures - Ayleid Assets
- Added Cleaned and Upscaled Textures - Saints and Seducers
- Added Unofficial Creation Club Patches - Saints and Seducers
- Added Realistic Water Two - Saints and Seducers Patch
- Added Cleaned and Upscaled Textures - Forgotten Seasons
- Added Unofficial Creation Club Patches - Forgotten Seasons
- Added Cleaned and Upscaled Textures - The Cause
- Added Cleaned and Upscaled Textures - Knights of the Nine
- Added Knight of the North - A Creation Club Quest Overhaul
- Added Cleaned and Upscaled Textures - Netch Leather Armor
- Added Morrowind Threads - A Creation Club Integration Mod
- Added Cleaned and Upscaled Textures - AA Daedric Mail
- Added Cleaned and Upscaled Textures - AA Dwarven Mail
- Added Cleaned and Upscaled Textures - AA Ebony Plate
- Added Cleaned and Upscaled Textures - AA Elven Hunter
- Added Cleaned and Upscaled Textures - AA Stalhrim Fur
- Added Cleaned and Upscaled Textures - AA Steel Soldier
- Added Cleaned and Upscaled Textures - AA Studded Dragonscale
- Added On A Crimson Trail
- Added Cleaned and Upscaled Textures - Rare Curios
- Added Unofficial Creation Club Patches - Rare Curios
- Added Curated Curios - A Creation Club Integration Mod
- Added The Cause - Rare Curios Patch
- Added The Cause - Flawed Varla Stone Integration

#### Website Changes

- **Installation:** Added references to the new optional profiles.
- **Customisation:** Slightly shuffled the contents of this page around.
- **Customisation:** Added Swap to Obsidian Weathers section.
- **Customisation:** Added Swap to Truth ENB section.
- **Customisation:** Added Completely Remove ENB section.
- **Creation CLub:** Added this page with instructions for the CC profile.
- **Documentation:** Updated for the new additions.
- **Screenshots:** Added eight new screenshots showcasing Obsidian Weathers/Truth ENB.

## Release 1.6.1

> 22/11/2021

Quick update to fix issues with ENB, it should download properly now. Sorry for the inconvenience!

#### Mod Changes

- Compiled with and requiring SSE 1.6.323 (latest)
- Updated ENBSeries binaries (no version number change)
- Updated Charge Dialogue Fix to 1.2
- Updated Assorted Mesh Fixes to 0.34

#### Website Changes

- **Installation:** Updated required version of SSE to 1.6.323 (latest)

## Release 1.6

> 20/11/2021

This update introduces Tate Taylor's superbrain solution for Skyrim AE. It was compiled with the latest version of SAE (1.6.318.0) in my actual root folder and LOTF's current supported version of SSE (1.5.97.0) in the Stock Game folder. With the small addition of meh's DLL Plugin Loader for some immensely big-brained binary patching action this allows LOTF to function without having to run the downgrade patcher first. The version in the Stock Game folder installed and used by LOTF will still be 1.5.97.0 until I eventually update to the latest one.

**Yes, I intend to update LOTF to SSE 1.6.318 / AE.** However, quite a few mods need updating first (currently the counter is at 13/40 and rising steadily). For more information on LOTF 2.0 / AE, please check my [November 2021 Update](https://www.patreon.com/posts/november-2021-58852886) post on Patreon.

The Immersive HUD MCM is now automated for anyone starting a new game (it does nothing for ongoing playthroughs). I also fixed the moreHUD Settings Loader (made a dumb mistake) so it should work as expected now.

**LATE NOTE:** LOTF 1.6 actually requires Skyrim SE 1.6.318.0 in your own root folder in order to install it. Updated the instructions accordingly.

#### Mod Changes

- Added SkyUI Ghost Bug Fix
- Added Animated Static Reload Fix
- Added Better Windhelm Meshes
- Added Immersive HUD - Settings Loader
- Added Immersive HUD - LOTF Preset
- Added Oxygen Meter
- Added Modern Toggle Walk-Run Fix
- Added Picta Series - Improved Sky Meshes
- Added Misc Tweaks - More Expensive Inn Prices (only works in new games)
- Added Misc Tweaks - More Realistic Animal Loot
- Added Sleeves for Guards
- Added Security Overhaul SKSE - Lock Variations
- Updated SKSE for Skyrim SE 1.5.97.0 to 2.0.20 (**STILL NO AE SUPPORT**)
- Updated SSE Display Tweaks to 0.5.0b
- Updated Dear Diary - Better More Informative Console to 1.3
- Updated SSE Engine Fixes to 5.8.0
- Updated powerofthree's Tweaks to 1.4
- Updated Equip Enchantment Fix to 1.3.2
- Updated Spell Perk Item Distributor to 5.1.0
- Updated NPC AI Process Position Fix to 4.06
- Updated Unequip Quiver SE to 1.6
- Updated Assorted Mesh Fixes to 0.33.1
- Updated ENBSeries to 0.465
- Compiled with SAE and meh's DLL Plugin Loader
- Now using a SSEDisplayTweaks_Custom.ini for config edits
- Enabled Grabbing Is Stealing po3's Tweaks
- Disabled sneak attack and critical hit messages in po3's Tweaks
- Moved Unequip Quiver SE to the SKSE & NET PLUGINS separator
- Moved No Lockpicking to the SKSE & NET PLUGINS separator
- Fixed moreHUD preset (should now actually auto-load in new saves)
- Forwarded HasWater flags for some cells that I'd previously missed in the CRP
- Reduced size of map markers by 25%
- Changed the Mod Organizer 2 executable icon

#### Website Changes

- **Installation:** Updated link to NVIDIA drivers to point to the English page rather than the German one
- **Installation:** Added Microsoft .NET 5.0 to the requirements section
- **Installation:** Removed instructions for the downgrade patcher (Skyrim SE 1.6.318.0 is now required)
- **Installation:** Added a reminder to launch the game at least once after (re)installing it
- **Customisation:** Updated "Uncap the framerate" section for the new SSEDisplayTweaks_Custom.ini

## Release 1.5

> 13/11/2021

This is mostly a maintenance update although I did add the fantastic **CoMAP** by Jelidity and Parapets as well as a brand-new installation guide. It is much shorter than the previous one on account of the Stock Game Folder system allowing us to skip several steps. It also accounts for the AE downgrade patcher.

Please for the love of Talos don't ask me when LOTF will get AE support.

#### Mod Changes

- Added Common Marker Addon Project (CoMAP)
- Updated SSEEdit to 4.0.4
- Updated SSE Display Tweaks to 0.4.17
- Updated NET Script Framework to 18
- Updated Skyrim Landscape and Water Fixes to 6.4.1
- Updated Assorted Mesh Fixes to 0.32.3
- Updated Static Mesh Improvement Mod Improvement Mod to 1.3.0
- Updated powerofthree's Tweaks to 1.3.3
- Updated Radiant - Candles to 2.2.0
- Updated Enhanced Vanilla Trees (no version change)
- Removed SMIM - Assorted Mesh Fixes Patch (redundant)
- Actually included the Blended Roads - Simplicity of Snow Patch

#### Website Changes

- **Installation:** Newly added with all instructions for LOTF, including the AE downgrade patcher
- **Screenshots:** Added new screenshots and headings for the side bar so the page is easier to navigate

## Release 1.4.2

> 24/10/2021

The butterfly update: In LOTF 1.4.2, I am adding some mods that improve critters in the world, how they move and where they can land. Did you know that Monarch butterfly wings were [upside down](https://staticdelivery.nexusmods.com/mods/110/images/54485-2-1401481905.jpg) in vanilla?

Also you no longer get my custom keybinds. I fixed that.

#### Mod Changes

- Added Umgak's Hanging Elves Ear Mesh Fix
- Added Wiseman303's Critter Fixes
- Added Butterflies Land True
- Added Butterflies Unchained
- Added Simplicity of Snow - Blended Roads Patch
- Updated Assorted Mesh Fixes to 0.32
- Updated Radiant - Candles to 2.1.0
- Updated DynDOLOD to 3 Alpha 53 (LOD was not regenerated)
- Fixed a dumb typo in the WABBAJACK_IGNORE_FILES.txt file name

## Release 1.4.1

> 16/10/2021

After yesterday's larger update, I have some fixes and previously missed mod updates for you today. Save safe, etc.

#### Mod Changes

Note that I only updated DynDOLOD and the DynDOLOD Resources, but did not regenerate LODs.

- Updated Skyrim Landscape and Water Fixes to 6.3
- Updated DynDOLOD Resources to Alpha 15
- Updated Shadows of Sunlight to 0.5
- Updated Simplicity of Snow to 0.4
- Updated ENBSeries (no version change)
- Updated DynDOLOD to 3 Alpha 48
- Added fixed moreHUD Settings Loader script (moreHUD MCM should no longer fail to initialise)
- Added my ControlMap_Custom.txt to the list of files ignored by Wabbajack so my keybinds are no longer applied to users' setups 

## Release 1.4

> 15/10/2021

This update brings a number of new addition that fit nicely within the scope of LOTF. I found that I could absolutely not live without **moreHUD** and added the mod along with a custom preset. You will now be able to see whether you already read a book, whether a book is a skill book and, if it is, which skill it improves. For enemies, their level and soul type is now displayed next to their health bar. When hovering over items that can be picked up, there will now be an indicator in the bottom right corner, informing you about your current carry capacity, how much weight the items would add, and whether you already have any items of the same type.

**Please note:** The moreHUD preset is applied automatically only in *new games*. In your ongoing playthroughs, please load it manually via the mod's MCM.

Visually, LOTF 1.4 adds the following improvements:

- Thanks to the new **Radiant - Candles** mod, candles now give off proper light and illuminate surrounding objects. You can find a comparison slider [here](https://imgsli.com/NzcwMjA). Note that this feature required me to enable Complex Particle Effects in ENB as well as increase the particle count INI setting which may cause a slight performance drop on low-end systems. However, I did not enable the Big Range setting so there will be no noticeable FPS loss on most PCs.
- The vanilla woven fences were notorious for their flickering which the Static Mesh Improvement Mod addresses but does not fully fix. I chose to add Mathy's meshes instead, **Skyrim 3D Misc - Woven Fence**, which are a lot more loose and should fix the flickering completely. There is a comparison slider [here](https://imgsli.com/NzcwMjE).
- Various assets related to spiders were fixed and improved by the mod **WEBS**. The titular spider webs are of higher quality and should no longer appear overbright. The mod also replaces the meshes for webbed dead bodies as some of them were outright broken in vanilla.
- **Simplicity of Snow** vastly improves the visuals and logic of projected snow on various objects. As a lightweight replacement for the more involved Better Dynamic Snow and No Snow Under Rooftops mods, it is well suited for LOTF's lightweight nature.

**The latest version of the .NET 5.0 Runtime is required.** This is because of the Scrambled Bugs update which now relies upon this. Please download it from [the official website](https://dotnet.microsoft.com/download/dotnet/5.0/runtime) and install it before updating LOTF.

#### Mod Changes

- Added WEBS
- Added High Gate Ruins Puzzle Reset Fix
- Added Static Mesh Improvement Mod Improvement Mod
- Added High Hrothgar - Fixed
- Added Skyrim 3D Misc - Woven Fence
- Added moreHUD
- Added Radiant - Candles
- Added Enhanced Vanilla Trees - Shrine to Peryite Nest Fix
- Added Simplicity of Snow
- Added Volcanic Tundra - Heat Wave Effects
- Added Misc Dialogue Edits
- Added Unofficial Material Fix - Improved Traps Patch
- Removed Wiseman303's Flora Fixes - Revamped - SMIM Patch (replaced by Static Mesh Improvement Mod Improvement Mod)
- Removed hank's gamepad and controller fixes
- Updated Spell Perk Item Distributor to 5.0.4
- Updated Scrambled Bugs to 14
- Updated DynDOLOD Resources to 3 Alpha 13
- Updated Assorted Mesh Fixes to 0.30.1
- Updated Relighting Skyrim to 1.2.1
- Updated College of Winterhold Quest Start Fixes to 0.2-1
- Updated DynDOLOD to 3 Alpha 47
- Updated ENBSeries (no version change)
- Temporarily set the hangingelvesear01.nif mesh (Skyrim Particle Patch) to hidden to fix a bug
- Enabled and tweaked ENB complex particle light effects
- Increased particle count (iMaxDesired) to 7500 in the SkyrimPrefs.ini
- Roboto Font Replacer is now disabled by default
- Fixed a few minor plugin conflicts
- Regenerated DynDOLOD

#### Website Changes

- **Introduction:** Added a warning about the new requirement of the .NET 5.0 Runtime.
- **Customisation:** Updated font replacer instructions, Roboto is now *disabled* by default
- **Documentation:** Updated accordingly for the recent mod changes.

## Release 1.3.1

> 19/09/2021

Just a quick update to fix the current issues with downloading ENB and some outputs.

#### Mod Changes

- Updated ENBSeries binaries to 0.463
- Updated Spell Perk Item Distributor to 5.0.3
- Updated Fixed Mesh Lighting to 1.4.2
- Updated NPC AI Process Position Fix to 4.05d
- Fixed TexGen and DynDOLOD output links

## Release 1.3

> 15/09/2021

This is a smaller update and will likely be the last one for the time being. I fixed the message when trying to drop a quest message so it does not just now show the raw string (was missing a dependency), removed the mod causing the purple waterfalls (couldn't be bothered to find the missing texture), updated a bunch of mods, and regenerated TexGen, DynDOLOD, and Occlusion with the latest version of DynDOLOD. I believe LOTF is in a pretty good place for now.

#### Mod Changes

- Added Scaleform Translation Plus Plus
- Added LeanWolf's Dawnbreaker ENB meshes
- Updated .NET Script Framework to 17
- Updated Disable USSEP Book to 1.1
- Updated Assorted Mesh Fixes to 0.26
- Updated College of Winterhold Quest Start Fixes to 0.2
- Updated DynDOLOD Resources to Alpha-12
- Updated Simple Horse Tweaks to 1.3
- Updated the Blacksmith Forge Water Patch Script and regenerated the patch
- Updated DynDOLOD to Alpha 41 and regenerated all LODs
- Removed horse walk movement tweak from the CRP
- Removed DynDOLOD Bright LOD Waterfall Fix
- Disabled the floating pot in High Hrothgar
- xLODGen is no longer packaged with the installer

## Release 1.2

> 10/09/2021

After some deliberation, I swapped out the previous skin overhauls (Lucid and Vitruvia) for the Tempered Skins combination. They are closer to vanilla and look better with LOTF's lighting.

I also fixed the purple waterfalls and improved the [book interface](https://imgsli.com/NzAzOTc).

#### Mod Changes

- Added ENB Helper
- Added Realistic Paper
- Added Blacksmith Forge Water Patch xEdit Script
- Added Convenient Reading
- Added Tempered Skins for Males
- Added Tempered Skins for Females
- Updated Minimal ENB for Obsidian Weathers to 1.2
- Updated Scrambled Bugs to 13
- Updated Enhanced Vanilla Trees to 2.2.1
- Removed Vitruvia - Skin Texture Overhaul for Males
- Removed Lucid Skin
- Tweaked the updated ENB preset
- Classic Sprinting Redone is now optional and disabled by default
- Generated the Blacksmith Forge Water Patch
- Regenerated TexGen and DynDOLOD

#### Website Changes

- **Customisation:** Added "Change sprinting from toggle to hold" option
- **Documentation:** Updated accordingly for the recent mod changes.
- **Screenshots:** Added a few more new screenshots.

## Release 1.1

> 06/09/2021

**Fixing the intro dialogue:**

So apparently increasing horse speed will mess up the intro carriage ride because the horses are too fast for the dialogue - who would have thought? I reverted *only* the forward walk speed tweak from Simple Horse Tweaks to vanilla which should fix it.

**New ENB preset:**

I also added an **ENB** preset in this update. If The Truth was still on the Nexus, it would have been part of the initial release, but with things as they are I had elected not to use an ENB at all. However, after some playing I realised that vanilla ambient occlusion crushes blacks on the character and some shadows to the point where it's just ugly as hell.

Thankfully, @Shade088 from our Discord server recommended [Minimal ENB for Obsidian Weathers](https://www.nexusmods.com/skyrimspecialedition/mods/37098) which turns out to be the perfect alternative. It does not affect colours (so you can also use it with any weather mod), but implements all those little improvements that ENB can bring to the table such as ambient occlusion. @Shade088 also provided tweaked water values to hide the distant water seams so I didn't even have to figure these out myself.

Since LOTF is using the Stock Game folder system, ENB is already installed for you and you do not have to move any files.

**This update is save-safe.**

#### Mod Changes

- Added deorder's MO2 plugins (largely for myself)
- Added Minimal ENB for Obsidian Weathers
- Added ENBSeries binaries
- Added Skyrim Particle Patch for ENB
- Added Skyrim Particle Patch for ENB - Assorted Mesh Fixes - Solitude Mesh Fixes Patch
- Added DynDOLOD Bright LOD Waterfall Fix
- Added Time Format Changer (disabled by default)
- Added Menu and Load Smoke Removed for ENB
- Added No Lockpicking (disabled by default)
- Removed Loading Screen Smoke Removed
- Disabled ambient occlusion in the INI files
- Replaced the MO2 splash screen with one specifically made for LOTF
- Actually hid the terrain LOD files overwriting AQWM

#### Website Changes

- **Introduction:** Removed LOTF in numbers section. No point maintaining this.
- **Introduction:** Added ENB Hotkeys section.
- **Introduction:** Fixed MCM instructions referencing removed mods.
- **Introduction:** Moved the customisation section to the new dedicated page.
- **Customisation:** Added new "Enable 24h time format" option.
- **Customisation:** Added new "Skip Lockpicking" option.
- **Documentation:** Added notes on the new ENB preset and my tweaks for it

## Release 1.0

> 04/09/2021

**First public release of LOTF.**

#### Mod Changes

- Now using the Stock Game folder system
- Now packaging all tools with the WJ installer
- Added NPC AI Process Position Fix
- Added Modern Clap Bug Fix
- Added Quality Cubemaps - HD Cube Maps
- Added Cathedral Night Sky
- Added Waymark - A Road Signs Mod
- Added HD Vanilla Tree Bark - ESRGAN AI Upscale
- Added Cathedral - Plants
- Added Cathedral - Mushrooms
- Added LOOT Preventifier
- Added Project Clarity - Architecture Textures Redone
- Added Project Clarity - Dungeon Textures Redone
- Added Project Clarity - Landscape Textures Redone
- Added Project Clarity - Clutter Textures Redone
- Added Project Clarity - Weapon Textures Redone
- Added Project Clarity - Armor Textures Redone
- Added Project Clarity - Clothing and Jewelry Textures Redone
- Added Project Clarity - Creature Textures Redone
- Added Project Clarity - Effect Textures Redone
- Added Simple Horse Tweaks
- Added Unequip Quiver
- Added Auto Input Switch
- Added Terrain Tamriel Extend
- Updated .NET Script Framework to 16
- Updated MCM Helper to 1.3.0
- Updated Assorted Mesh Fixes to 0.25
- Updated Fixed Mesh Lighting to 1.4.1
- Updated Landscape Fixes For Grass Mods to 4.9
- Updated Enhanced Vanilla Trees to 2.2.0
- Removed Base Coat
- Removed Animated Forge Water
- Removed Point the Way
- Removed Arena - An Encounter Zone Overhaul
- Removed Apothecary - An Alchemy Overhaul
- Removed Radiant Requirements MCM
- Removed Radiant Requirements MCM - TPF Preset
- Removed Apothecary as a master from the CRP
- Fixed a conflict between Simple Horse Tweaks and Audio Overhaul for Skyrim
- Regenerated INI files with BethINI
- Regenerated terrain LOD, TexGen, DynDOLOD, Occlusion
- New colour theme for the MO2 separators
- New MO2 splash screen replacer

#### Website Changes

- Updated the Introduction (noted that LOTF uses the Stock Game folder system)
- Updated the Documentation (removal of Apothecary and Arena, etc).
- Added one new screenshot to the showcase page.

## Wabbajack Test

> 22/08/2021

- Initial release for Wabbajack testing.