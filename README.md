# MeloNX HDD test builds

This repository is a small, reproducible build wrapper for the official MeloNX source at [starforgejo.dev/projects/MeloNX](https://starforgejo.dev/projects/MeloNX.git).

It does not replace or rebrand upstream source. The workflow fetches the pinned official source revision, builds the complete iOS app, and verifies that the official `MeloNXRamDonor` helper extension is embedded before packaging an unsigned test IPA.

The upstream project provides direct security-scoped folder access on iOS, so a user-selected external drive folder can be linked and scanned without copying game files into the app’s internal storage.

No games, firmware, title keys, signing certificates, or JIT credentials are included. The IPA artifact must be signed by the device owner using their chosen sideloading method. Please see the upstream source for license and attribution information.
