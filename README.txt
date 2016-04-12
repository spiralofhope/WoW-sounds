--
-- INTRO
--

I was sick and tired of a whole range of sounds.  I did a lot of searching and I found "Silencer" for Hunter guns.  From there, I was able to hunt down a number of annoying sounds and package them all together.

With many thanks to AudioX II, without which this would have been bloody annoying to do.
http://wow.curse.com/downloads/wow-addons/details/audiox.aspx

To use, simply unzip this to your "World of Warcraft\Data\Sound" directory.  By default, this directory is completely empty.  On startup, when appropriately-named .wav files are seen by the game, it will use the new sound instead.

If you want muted sounds, check out
- combat only:  http://www.wowinterface.com/downloads/info18781-MutedSounds-combatonly.html
- all:  http://www.wowinterface.com/downloads/info18782-MutedSounds-all.html


--
-- TO DO
--

- remove the fucking repair mount noises

Completely silence the login screen
- http://www.wowinterface.com/downloads/info11123-SilentLoginScreen.html#info is Wrath..
Ambience\..


Additional mount jump-in-place sounds:
- Cat.. (and cat growl thing, are there any other similar sounds?)
-- the new guild cat mount
- Pony
- horse..
- ... all the Horde stuff
- more?
- silithid pet combat sounds

Emotes:
- chicken

Misc:
- the mana table ambient sound
- harp sound (piccolo)
- Dual-requests
- I've probably muted too much for tradeskills.  I may be able to mute _others_ without muting _onesself_.  To be researched..
- Disenchanting
- smelting, the generic crafting sound (like with blacksmiths making grinding stones)
- enchanting
- The pet-summoning whistle (hunter pet, crusader non-combat)
- mini thor non-combat pet


--
-- POSSIBLY-CONTROVERCIAL CHANGES
--

The music at the login screen:
Music\cataclysm\MUS_Shattering_UU01.mp3

Tradeskills\CookingPrepareA..C
Tradeskills\AlchemyCraftingA..C
Tradeskills\BlackSmithCraftingA..E
Tradeskills\Engineering
Tradeskills\Leatherworking
Tradeskills\Tailoring

Universal\TradeskillLearnRecipeLoop

Muting the miners in Exodar also mutes all player mining:
\Spells\Tradeskills\MiningHitA..E

The error sounds:

Spells\Fizzle\*


--
-- MISC
--

Blacksmiths at anvils (forced to mute both players and NPCs)

Gun Silencer/Suppressor
http://wow.curse.com/downloads/wow-addons/details/silencer.aspx
There are a few Gun Silencer mods that replace Blizzard's ear deafening default gun sounds, and most of the ones I have found weren't very high quality. So I decided to make my own, with HI-DEF silencer recordings. 
- 1 Silenced Gun Shot (M4A1 Carbine)
- 3 Unique Reload Sounds 

No More Stomp Sounds
http://wow.curse.com/downloads/wow-addons/details/nmss.aspx
Tired of hearing Devilsaurs, Magma Core Hounds and all these exotics pets stomping ? Well that mod is made for you :D
[Thanks for saving me the bother of testing if 0-byte wav files would work.]

Worgen Sniff Mute
http://cladhaire.wowinterface.com/downloads/info18989-WorgenSniffMute.html


--
-- MOUNTS
--

Quiet That Horse!
http://wow.curse.com/downloads/wow-addons/details/qth.aspx
The shriek of the Death Knight Charger being summoned was novel and interesting for a while, but it quickly grew incredibly grating. This tiny modification changes the spell noise to a more subdued, but still atmospheric, roll of muted thunder.

Quiet That Horse! was re-used for the paladin mount

Mount jumping-in-place:
- Elekk
- Horse
- Tyrael's Charger

--
-- NOTES
--

Interface\Aggro_Enter_Warning_State
Interface\Aggro_Pulled_Aggro



--
-- CHANGELOG
--

xxx
5.2
- Misdirection:
    Spells/Misdirection_Inpact_Head.ogg
- Changed .wmv to .ogg, empty files still work.


30300-2
- Added a bunch more tradeskills
- New pets: Pandaren Panda, Perky Pug,
- New mounts: Mammoth, MechaStrider, Motorcycle, Ram - both the jump-in-place and idle loop.  Not completely tested, may have muted too much.
- New flying mounts: RocketMount, Gyrocopter idle standing and idle flying loops.  Untested.
- Removed Chakra.  This pre-cast sound also removes the sound from various other spells.
-- Thanks to http://wow.curse.com/downloads/wow-addons/details/humbuzz-b-gone.aspx
- Removed the /train sound
-- Thanks to http://www.wowinterface.com/downloads/info12077-TrainWreck.html
- Water elemental idle sound.
- Mount and dismount sound (Spells\SpiritWolf.wav)
-- Thanks to http://wow.curse.com/downloads/wow-addons/details/mountnoise-b-gone.aspx
- More mount stuff: Mekgineer's Chopper, Mimiron's Head (actual Mimiron too), Turbo-Charged Flying Machine Control, Goblin Turbo-Trike.  I chose to keep the actual movement and combat/sidecar-dismount sounds though.
-- Thanks to http://www.wowinterface.com/downloads/info16194-QuietMounts.html
- Lil' XT (and the real XT002 Deconstructor)
-- Thanks to http://wowinterface.com/downloads/info16491-SilentXT.html
- ALL mount "specials"
-- Especially the turtle mount special - the stupid squeaky plastic cartoon sound.

30300-1
