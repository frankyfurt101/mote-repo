# Mote packages

Public distribution files for the experimental Mote app on rootless iOS 16.
This repository contains the compiled package, APT indexes and attribution.
Development sources are maintained separately.

## Install

After GitHub Pages has finished publishing, add this source in Sileo:

https://frankyfurt101.github.io/mote-repo/

Open **Sileo → Sources → +**, paste that URL, refresh, and install **Mote**.
Version: `0.1.2-1`, architecture: `iphoneos-arm64`.

The app installs under `/var/jb/Applications/Mote.app` while the existing
rootless jailbreak is active. Version 0.1.0 installed on the XR but showed a blank screen. Version 0.1.1
updates startup and file loading; its XR launch and sensors still need testing.

## Attribution

The bundled FlyWire circuit and derivatives are CC BY-NC 4.0.
See [ATTRIBUTION.txt](ATTRIBUTION.txt) for the original sources and credits.
The curated circuit constrains an authored simulation; this is not a complete
or biologically faithful animal brain simulation.
