# empty-classname-fixer

fixes this crashing the server when a map has an empty classname entity (`"classname" ""`)

some maps that have this problem:
```
bhop_blueblocks.bsp
bhop_catalyst_nomusic.bsp
bhop_connectivity_fix.bsp
bhop_continuity.bsp
bhop_cys_nonstop.bsp
bhop_duble_buble3.bsp
bhop_dron.bsp
bhop_ins_fy_snow5.bsp
bhop_ins_fy_snow9.bsp
bhop_ins_fy_snow10.bsp
bhop_splrez.bsp
bhop_narkozzz.bsp
bhop_p06_norng.bsp
bhop_panda.bsp
kz_bhop_smallblocks.bsp
xc_blizzard.bsp
```

![Error box message that says "classname missing from entity!"](classname_missing_from_entity_error_box.png)

requires sourcescramble https://github.com/nosoop/SMExt-SourceScramble
- sourcescramble_manager.sp/.smx
- sourcescramble.ext.dll/.so
