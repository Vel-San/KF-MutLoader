# KF-MutLoader

Optimized version of 'MutLoader' originally made by Flame &amp; Essence, slightly modified by Vel-San;

- Usage with KFMapVoteV2

```unrealscript
GameConfig=(GameClass="KFMod.KFGameType",Prefix="KF",Acronym="KF",GameName="Easy",Mutators="MutLoader.MutLoader",Options="Difficulty=1")
GameConfig=(GameClass="KFMod.KFGameType",Prefix="KF",Acronym="KF",GameName="Normal",Mutators="MutLoader.MutLoader",Options="Difficulty=2")
```

No need to put any other mutators in the list of MapVoteV2. What's important is the GameType + Difficulty.

## Changes from the original version

- Better support with MapVoteV2
- ServerName change with every config
