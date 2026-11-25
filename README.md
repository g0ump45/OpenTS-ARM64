# OpenTS-ARM

Experimental ARM64 PortMaster port of OpenTS-A, the Tiberian Sun engine.

## Test package

Download **[OpenTS-ARM-PortMaster-candidate.zip](./OpenTS-ARM-PortMaster-candidate.zip)**. It contains the PortMaster launcher, game executable, source archive, metadata, and license files.

## Source code

The source snapshot is also available separately as **[OpenTS-ARM-source.tar.gz](./OpenTS-ARM-source.tar.gz)**. Extract it to access the full source tree.

## Requirements and game files

- ARM64 Linux handheld with glibc 2.34 or newer.
- SDL2 supplied by the device firmware.
- A legally obtained copy of Tiberian Sun. The game data is not included. Copy the files into `ports/opentsa/data/` on the device, with `TIBSUN.MIX` directly in that folder.

## Status

The package build, archive integrity, launcher syntax, and PortMaster metadata checks passed. Direct R36S testing and the broader firmware compatibility matrix are still pending.
This repository is private and intended for development and testing. This candidate is not an official PortMaster release.
