# Large Bucket Fast Fertilize

A tiny mod for **RuneScape: Dragonwilds**. The Large Compost Bucket now discharges **25 fertilizer per tick**, like the higher-tier watering cans. Fertilizing one 50-fertilizer farm plot takes **two ticks** instead of one big dump.

Capacity is unchanged (300). Nothing else is touched. The mod replaces a single item asset, `ITEM_Bucket_Compost_Big`.

## Install

**Manual:** copy `ZZ_LargeBucketFastFertilize_P.pak`, `.ucas` and `.utoc` (from `mod/`) into

`...\steamapps\common\RSDragonwilds\RSDragonwilds\Content\Paks\~mods\`

**Vortex:** drag `release/LargeBucketFastFertilize_v1.0.0.zip` into the Mods tab. The zip carries the path `RSDragonwilds/Content/Paks/~mods/`.

To confirm it loaded, search `RSDragonwilds\Saved\Logs\RSDragonwilds.log` for `ZZ_LargeBucketFastFertilize`; you should see a mounted IoStore container.

## Compatibility

- Overrides the Large Compost Bucket item only. It may conflict with other mods that edit `ITEM_Bucket_Compost_Big`.
- Game updates that change that asset can break or revert the mod.

## Uninstall

Delete the three files from `~mods`.

## Disclaimer

Unofficial fan-made mod, not affiliated with or endorsed by Jagex. RuneScape and Dragonwilds are Jagex's. The mod contains one modified item data asset from the game. Use at your own risk, and not on official servers where mods aren't allowed.
