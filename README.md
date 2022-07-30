# AdditionsPack-lih

_The Leben im Holz [AdditionsPack](https://www.curseforge.com/minecraft/mc-mods/additions-mod)_

## Updating

1. Increment version in `Leben Im Holz - Extra holzig/version.properties`
2. \[Ingame\] Main Menu » ++ » Leben im Holz Extra holzig v1.0 » Show to Others
3. Enter `1.0` as version (TechnicLauncher won't delete the old pack otherwise)

## Modifying Blocks

When saving the changes of a block, the value `hardness` will get lost.
To set the hardness again, open the block file under `Leben Im Holz - Extra holzig/data/blocks/lih-[name].json`
and add the value to the root curly brackets `"hardness": <float>`.