# OpenTS-ARM

Experimental ARM64 PortMaster port of OpenTS-A, the Tiberian Sun engine.

## Test package

Download **[OpenTS-ARM-PortMaster-candidate.zip](./OpenTS-ARM-PortMaster-candidate.zip)**. It contains the PortMaster launcher, game executable, source archive, metadata, and license files.

## Requirements and game files

- ARM64 Linux handheld with glibc 2.34 or newer.
- SDL2 supplied by the device firmware.
- A legally obtained copy of Tiberian Sun. The game data is not included. Copy the files into `ports/opentsa/data/` on the device, with `TIBSUN.MIX` directly in that folder.

## Status

The package build, archive integrity, launcher syntax, and PortMaster metadata checks passed. Direct R36S testing and the broader firmware compatibility matrix are still pending. The included screenshot is a temporary candidate image; replace it with a capture from the target device before submitting to the PortMaster catalogue.

This repository is a private development/test repository, not an official PortMaster release.
