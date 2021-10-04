# About this repository

Like the description of the repository says, I made it to gather whatever super small mods I end up doing as I test out stuff led by my endeavors developing stuff for the [Pokeemerald-expansion battle_engine](https://github.com/rh-hideout/pokeemerald-expansion/tree/battle_engine).

Don't expect anything at all.

Summary:

* `000400000011C400/romfs/a/0/1/3`: Changes the wild encounters of Pokémon Omega Ruby's Route 101 with Rayquaza.
  * Reason: I needed to test out some behaviors of the Air Lock ability.

* `000400000011C400/romfs/a/1/9/1`: Changes the first level up move of Pokémon Omega Ruby's Poochyena to Water Pulse.
  * Reason: I needed to test out some behaviors of the Strong Winds weather condition.

* `000400000011C400/romfs/a/1/9/5`: Changes the typing of Pokémon Omega Ruby's Mega Rayquaza to Fire/Flying.
  * Reason: Same as above.

## Notes, Clarifications, Et cetera

Files terminated in "`_og`" are clean copies made to quickly restore things out.

Also, these mods are made on my copy of Omega Ruby which has the v1.4 update installed. That may or may not make these mods incompatible with older versions, idk.

Once I accumulate enough mods I'll probably need to start to make folders to put copies of these files in. This process doesn't give much room for dynamicity. What that means is that I'm not exporting specific changes here, I'm exporting entire files containing wild encounter, base stats and level up learnset changes.

## Usage

The quickest way is to load them through Citra.

Drop the `000400000011C400` folder into `Citra\user\load\mods`, boot up the game, and you're ready to go.

## Credits

* [kwsch](https://github.com/kwsch): [Pk3DS](https://github.com/kwsch/pk3DS)
* [Blurose](https://github.com/BluRosie): Thanks to [their pokemon-x-mods repository](https://github.com/BluRosie/pokemon-x-mods) is that I learned that you can do things like this.