# valve_addon

HLDM: Upgraded Resources

[![screenshot-1](/thumbnail-1)](/screenshot-1)
[![screenshot-2](/thumbnail-2)](/screenshot-2)

* Updated textures.
* Models from Black Mesa - optimized for FOV 110.
* Minor audio updates.
* New high-resolution crosshairs with outlines.
* Alternative RPG crosshair.
* Tested with Steam up-to-date post-**Anniversary** release.


## Install with GIT

Open terminal at `C:/Program Files (x86)/Steam/steamapps/common/Half-Life` or where
you have Half-Life installed.

```console
git clone https://github.com/raub/valve_addon.git
```

The resulting directory should be: `C:/Program Files (x86)/Steam/steamapps/common/Half-Life/valve_addon`.


## Unpack from ZIP

Unpack into `C:/Program Files (x86)/Steam/steamapps/common/Half-Life` or where
you have Half-Life installed.

The resulting directory should be: `C:/Program Files (x86)/Steam/steamapps/common/Half-Life/valve_addon`.


## Game Settings

In order for `valve_addon` folder to be enabled in Half-Life,
navigate to `Options -> Content`, and tick `Allow custom addon content`.

Otherwise it is still possible to extract the files directly to the `valve` directory,
it will work, although the former approach is cleaner.

Ingame setting `r_detailtextures 1` should be assigned - this is done automatically by the
modified `valve_addon/autoexec.cfg`. If any other config overrides it to become `0` - the
detail textures, such as cracks and small details, wont be visible.


## References

[Green Crosshairs](https://gamebanana.com/mods/309097) - for this pack, the croshairs
were manually upscaled and outlined.

[New Laser Dot](https://gamebanana.com/mods/11526).

[HD Half-Life retextures pack](https://gamebanana.com/mods/6738).

[Black Mesa Weapons Pack for Half-life 1](https://www.moddb.com/mods/black-mesa-weapons-pack-for-half-life-1) - for
this pack, the models were manually adjusted using
[HLMV](https://www.moddb.com/games/half-life/downloads/half-life-model-viewer-210).
The models are optimized for FOV 110 (`default_fov 110` in console).
Some of the models are taken from `valve_hd` folder - where they look better.
Most of the sounds from this model pack were removed in favor of the original ones.
