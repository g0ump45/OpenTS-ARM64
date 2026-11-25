# OpenTS-A

An ARM64 Linux handheld port of [OpenTS](https://github.com/OpenTS-Developers/OpenTS), maintained by **GEARS0FUMP45**, for Command & Conquer: Tiberian Sun and Firestorm.

This build brings the OpenTS-A game engine and handheld controls to PortMaster-compatible Linux devices.

## Install

1. Use an **ARM64 Linux handheld** with glibc 2.34 or newer and firmware-provided SDL2.
2. Download **[OpenTS-ARM-R36S-Verified.zip](https://github.com/g0ump45/OpenTS-ARM/releases/download/v0.1.0-portmaster-test.1/OpenTS-ARM-R36S-Verified.zip)** from the [release page](https://github.com/g0ump45/OpenTS-ARM/releases/latest).
3. Extract the ZIP contents into your device's `ports/` folder. Keep `OpenTS-A.sh` and the `opentsa/` folder together.
4. Copy the **complete game-data set** from your installed Tiberian Sun folder into `ports/opentsa/data/`. Do not copy only `TIBSUN.MIX`: the game also needs the other data archives and files, such as MIX archives, maps, movies, audio, INI files, and loose game assets. If you want to play Firestorm, include its expansion data too.
5. Keep `TIBSUN.MIX` directly in `ports/opentsa/data/`. The launcher checks for that file as a quick presence check; it does not mean that file alone is enough to run the game.
6. Launch **OpenTS-A** from your handheld's Ports menu.

The game files are not included. Use files from a copy of Tiberian Sun that you own.

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
