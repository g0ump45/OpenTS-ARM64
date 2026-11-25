# OpenTS-A

An ARM64 Linux handheld port of [OpenTS](https://github.com/OpenTS-Developers/OpenTS), maintained by **GEARS0FUMP45**, for Command & Conquer: Tiberian Sun and Firestorm.

This build brings the OpenTS-A game engine and handheld controls to PortMaster-compatible Linux devices.

## Install

1. Use an **ARM64 Linux handheld** with glibc 2.34 or newer and firmware-provided SDL2.
2. Download **[OpenTS-ARM-R36S-Verified.zip](https://github.com/g0ump45/OpenTS-ARM/releases/download/v0.1.0-portmaster-test.1/OpenTS-ARM-R36S-Verified.zip)** from the [release page](https://github.com/g0ump45/OpenTS-ARM/releases/latest).
3. Extract the ZIP contents into your device's `ports/` folder. Keep `OpenTS-A.sh` and the `opentsa/` folder together.
4. Copy the contents of your Steam **Command & Conquer: Tiberian Sun and Firestorm** install folder into `ports/opentsa/data/`, keeping the game-data files together.

## Required game files

Include the complete Tiberian Sun and Firestorm game data. Your install folder should contain these archives:

- `TIBSUN.MIX` and `GMENU.MIX`
- Firestorm expansion archives: `EXPAND01.MIX`, `EXPAND02.MIX`, `EXPAND03.MIX`, `E01SCD01.MIX`, `E01SCD02.MIX`
- `MAPS01.MIX`, `MAPS02.MIX`, `maps03.mix`
- `MOVIES01.MIX`, `MOVIES02.MIX`, `movies03.mix`
- `MULTI.MIX`, `PATCH.MIX`
- `SCORES.MIX`, `SCORES01.MIX`
- `sidecd01.mix`, `sidecd02.mix`, `wdt.mix`, `wdtvox.mix`

Put all the game-data files in this location:

```
ports/opentsa/data/TIBSUN.MIX
ports/opentsa/data/GMENU.MIX
ports/opentsa/data/EXPAND01.MIX
ports/opentsa/data/...
```

Game files are not included. however this game has been release as freeware.
https://cnc-comm.com/tiberian-sun/downloads/the-game/installer

## Controls

Configure button assignments and cursor speed in the in-game **Options > Controls** menu. The default mapping uses the D-pad and left stick to move the cursor, **A** to select, **B** to cancel or right-click, and **Select** for the on-screen groups and base controls.

## Tested device

Confirmed working on an **R36S Clone running ArkOS4Clone-20261008**. Other handhelds and firmware versions have not yet been verified. This is an unofficial community build and is not an official PortMaster catalogue release.

## Source code

The source snapshot is available as **[OpenTS-ARM-source.tar.gz](https://github.com/g0ump45/OpenTS-ARM/releases/download/v0.1.0-portmaster-test.1/OpenTS-ARM-source.tar.gz)**.

## Support

Support is optional. All features stay free. Donations do not buy game files or content. Visit [Ko-fi](https://ko-fi.com/gears0fump45) or [GitHub Sponsors](https://github.com/sponsors/g0ump45).

## Credits and licence

Credit to the [OpenTS developers](https://github.com/OpenTS-Developers/OpenTS) for the engine this port builds on. **Westwood Studios** created Tiberian Sun and Firestorm; **Electronic Arts** published them. OpenTS-A is unofficial and is not affiliated with or endorsed by Electronic Arts.

The package includes the applicable licence and third-party notices. Game names and assets belong to their respective rights holders.
