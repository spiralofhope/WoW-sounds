Modifications (mostly muting) various World of Warcraft sounds.



# Intro

With many thanks to [AudioX II](https://wow.curseforge.com/projects/20522), without which this would have been bloody annoying to do.

If you want muted sounds, check out:

  - [Muted Sounds - Combat](http://www.wowinterface.com/downloads/info18781)
  - [Muted Sounds - Everything](http://www.wowinterface.com/downloads/info18782)



# Installation/Usage

This is not an AddOn.

To install/use it, unzip this to your `World of Warcraft\Data\Sound\_retail_` directory.  Perhaps that is `C:\Program Files (x86)\World of Warcraft\_retail_\Sound`.

By default, this `Sound` directory is completely empty.  On startup, when appropriately-named `.ogg` files are seen by the game, it will use those new sounds instead.

There are no in-game options.  If you want to make your own changes, you'll have to delve into the structure of your `Sound` directory and remove or replace your choice of `.ogg` files.



# Possibly-controversial changes

- `Tradeskills\CookingPrepareA..C`
- `Tradeskills\AlchemyCraftingA..C`
- `Tradeskills\BlackSmithCraftingA..E`
- `Tradeskills\Engineering`
- `Tradeskills\Leatherworking`
- `Tradeskills\Tailoring`

- `Universal\TradeskillLearnRecipeLoop`

The music at the login screen:

- `Music\cataclysm\MUS_Shattering_UU01.mp3`

Muting the miners in Exodar also mutes all player mining:

- `\Spells\Tradeskills\MiningHitA..E`

The error sounds:

- `Spells\Fizzle\*`



# Misc

- Blacksmiths at anvils (forced to mute both players and NPCs)

- [M4A1 Carbine Silencer/Suppressor/Crossbow/Bow](https://wow.curseforge.com/projects/61326)
  -  There are a few Gun Silencer mods that replace Blizzard's ear deafening default gun sounds, and most of the ones I have found weren't very high quality. So I decided to make my own, with HI-DEF silencer recordings. 
  -  1 Silenced Gun Shot (M4A1 Carbine)
  -  3 Unique Reload Sounds 

- [No More Stomp Sounds](https://wow.curseforge.com/projects/16409)
  -  Tired of hearing Devilsaurs, Magma Core Hounds and all these exotics pets stomping ? Well that mod is made for you :D
  -  [Thanks for saving me the bother of testing if 0-byte wav files would work.]

- [Worgen Sniff Mute](http://wowinterface.com/downloads/info18989)



# Mounts

- [Rockdelver's](https://www.curseforge.com/members/Rockdelver) Quiet That Horse!
  -  [archive](https://web.archive.org/web/20091208065745/wow.curse.com/downloads/wow-addons/details/qth.aspx)
  -  [down](http://wow.curse.com/downloads/wow-addons/details/qth.aspx)
  -  [down](https://www.curseforge.com/projects/qth/)
  -  "The shriek of the Death Knight Charger being summoned was novel and interesting for a while, but it quickly grew incredibly grating. This tiny modification changes the spell noise to a more subdued, but still atmospheric, roll of muted thunder."
  -  Quiet That Horse! was re-used for the paladin mount
  -  I notice there is [Kill That Horse!](https://www.curseforge.com/projects/19772), which was not checked.  It is `Spells\DeathKnight_SummonWarHorse_Impact_Base.ogg`

- Mount jumping-in-place:
  - Elekk
  - Horse
  - Tyrael's Charger



# Manually muting with LUA code

This example code will work until you restart the client:

```
local sounds = {
	569772,  -- sound/spells/fizzle/fizzleholya.ogg
	569773,  -- sound/spells/fizzle/fizzlefirea.ogg
	569774,  -- sound/spells/fizzle/fizzlenaturea.ogg
	569775,  -- sound/spells/fizzle/fizzlefrosta.ogg
	569776,  -- sound/spells/fizzle/fizzleshadowa.ogg
}

for _, fdid in pairs( sounds ) do
	MuteSoundFile( fdid )
end
```

If you wanted something that is re-applied every restart, then you'd have to use an AddOn of some kind, like [DevPad](https://github.com/spiralofhope/_DevPad/)
