# empty-classname-fixer

fixes this crashing the server when a map has an empty classname entity (`"classname" ""`)

some maps that have this problem:
```
bhop_blueblocks.bsp
bhop_connectivity_fix.bsp
bhop_continuity.bsp
bhop_cys_nonstop.bsp
bhop_dron.bsp
bhop_narkozzz.bsp
bhop_splrez.bsp
xc_blizzard.bsp
```

![Error box message that says "classname missing from entity!"](classname_missing_from_entity_error_box.png)

this says it's caused by stripper:source but idk https://github.com/alliedmodders/stripper-source/issues/14

requires sourcescramble https://github.com/nosoop/SMExt-SourceScramble
- sourcescramble_manager.sp/.smx
- sourcescramble.ext.dll/.so
