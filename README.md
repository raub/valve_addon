# valve_addon

HLDM: Upgraded Resources

[![screenshot-1](/thumbnail-1.jpg)](/screenshot-1.jpg)
[![screenshot-2](/thumbnail-2.jpg)](/screenshot-2.jpg)

* Updated textures / optional detail textures.
* Models from Black Mesa - optimized for FOV 110.
* Minor audio updates.
* New high-resolution crosshairs with outlines.
* Alternative RPG crosshair.
* Tested with Steam up-to-date post-**Anniversary** release.
* BugfixedHL - client.dll


## Install with GIT

Open terminal at `C:/Program Files (x86)/Steam/steamapps/common/Half-Life` or where
you have Half-Life installed.

```console
git clone https://github.com/raub/valve_addon.git
```

The resulting directory should be: `C:/Program Files (x86)/Steam/steamapps/common/Half-Life/valve_addon`.


## Unpack from ZIP

Pick from [the Releases page](https://github.com/raub/valve_addon/releases).

Unpack into `C:/Program Files (x86)/Steam/steamapps/common/Half-Life` or where
you have Half-Life installed.

The resulting directory should be: `C:/Program Files (x86)/Steam/steamapps/common/Half-Life/valve_addon`.


## Game Settings

In order for `valve_addon` folder to be enabled in Half-Life,
navigate to `Options -> Content`, and tick `Allow custom addon content`.

Otherwise it is still possible to extract the files directly to the `valve` directory,
it will work, although the former approach is cleaner.

In console: `exec addon.cfg` - this will automatically apply the settings from [addon.cfg](/addon.cfg).
Otherwise you can use your own settings, or execute only part of the config manually.

**Config Notes:**
* `r_detailtextures 1` enables the detail textures (`0 - to disable`).
* `cl_cross_enable 0` enables the sprite crosshairs (`1 - to use BugfixedHL crosshair`).


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

[BugfixedHL-Rebased](https://github.com/tmp64/BugfixedHL-Rebased).
