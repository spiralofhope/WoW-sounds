--
-- INTRO
--

I was sick and tired of a whole range of sounds.  I did a lot of searching and I found "Silencer" for Hunter guns.  From there, I was able to hunt down a number of annoying sounds and package them all together.

With many thanks to AudioX II, without which this would have been bloody annoying to do.
http://wow.curse.com/downloads/wow-addons/details/audiox.aspx

To use, simply unzip this to your "World of Warcraft\Data\Sound" directory.  By default, this directory is completely empty.  On startup, when appropriately-named .wav files are seen by the game, it will use the new sound instead.

--
-- TO DO
--

Additional mount jump-in-place sounds:
- Charger (Death Knight)
- Mechano Hog (motorcycle)
- Cat.. (and cat growl thing, are there any other similar sounds?)
- Pony
- Perhaps the new sparkly-scam mount
- ... all the Horde stuff
- more?

Mount idle sounds:
- Mechano Hog
- rocket
- copter
- more?

Emotes:
- train
- chicken

Misc:
- Dual-requests
- The opening dragon sound (yes it's doable!)
- I've probably muted too much for tradeskills.  I may be able to mute _others_ without muting _onesself_.
- Disenchanting
- Learn what the RocketMount idle-flying loop is, if any.  Needs to be tested.  I don't want to mute the regular flying sound, just the idle-flying sound.
- smelting, the generic crafting sound (like with blacksmiths making grinding stones)
- enchanting
- The pet-summoning whistle (hunter pet, crusader non-combat)
- "Lil' Smokey" non-combat pet


--
-- POSSIBLY-CONTROVERCIAL CHANGES
--

Tradeskills\CookingPrepareA..C
Tradeskills\AlchemyCraftingA..C
Tradeskills\BlackSmithCraftingA..E
Tradeskills\Engineering
Tradeskills\Leatherworking
Tradeskills\Tailoring

Universal\TradeskillLearnRecipeLoop

Muting the miners in Exodar also mutes all player mining:
\Spells\Tradeskills\MiningHitA..E


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

--
-- NOTES
--

Interface\Aggro_Enter_Warning_State
Interface\Aggro_Pulled_Aggro


--
-- CHANGELOG
--

30300-2
- Added a bunch more tradeskills
- New pets: PandarenPet.  Damn I hate that thing.
- New mounts: Mammoth, MechaStrider, MotorcycleVehicle, Ram - both the jump-in-place and idle loop.  Not completely tested, may have muted too much.
- New flying mounts: RocketMount, Gyrocopter idle standing and idle flying loops.  Untested.

30300-1
