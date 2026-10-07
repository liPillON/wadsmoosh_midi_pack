# wadsmoosh\_midi\_pack


A pwad for jpLeBreton's original WadSmoosh, adding the various community's MIDI Packs music tracks.

Load it after the `doom_complete.pk3` iwad, wich is assumed to have been generated:

* using all official 4 iwads
* adding NERVE.WAD and SIGIL.WAD
* compiling the 20 Master Levels WADs using the XASER level progression



## Level Progression
The XASER level progression has been adopted by the latest official, kex-based source port released by ID/NightDive in 2024.

WadSmoosh IWADs generated using the PSN level progression are NOT supported.

For more information about the different level progressions, see [here](https://doomwiki.org/wiki/Master_Levels_for_Doom_II#Level_progression)



## Implementation Details
With the exception of SIGIL (wich already comes with its own midis) all other mapsets have had their soundtracks tweaked by using the following criteria:

* DOOM, DOOM2, TNT: music has been replaced only for maps that reused tracks from earlier maps/episodes/games
* NERVE, PLUTONIA, MasterLevels: the whole soundtrack has been replaced using the full release of each midi pack


The following enhancement have been made to the mapinfo definitions, where needed:

* game/episode-specific intermission screen music (D_INTER/D_DM2INT) using the `defaultmap` command 
* cluster-specific text screen music (D_VICTOR/D_READ_M) setting the `defaultmap` property 



## Credits
All contributors are credited in the pk3 by embedding the same .txt files found on each /idgames download.

More information about each MIDI Pack:

* [https://doomwiki.org/wiki/Ultimate\_MIDI\_Pack](https://doomwiki.org/wiki/Ultimate_MIDI_Pack)
* [https://doomwiki.org/wiki/.MID\_the\_Way\_id\_Did](https://doomwiki.org/wiki/.MID_the_Way_id_Did)
* [https://doomwiki.org/wiki/No_Rest_for_the_Living_Community_MIDI_Pack](https://doomwiki.org/wiki/No_Rest_for_the_Living_Community_MIDI_Pack)
* [https://doomwiki.org/wiki/Master_Levels_for_Doom_II_25th_Anniversary_MIDI_Pack](https://doomwiki.org/wiki/Master_Levels_for_Doom_II_25th_Anniversary_MIDI_Pack)
* [https://doomwiki.org/wiki/Plutonia\_MIDI\_Pack](https://doomwiki.org/wiki/Plutonia_MIDI_Pack)
* [https://doomwiki.org/wiki/TNT:\_Evilution\_MIDI\_Pack](https://doomwiki.org/wiki/TNT:_Evilution_MIDI_Pack)



## More info

First posted [here](https://forum.zdoom.org/viewtopic.php?p=1241562#p1241562) using my old zdoom forums alias.



