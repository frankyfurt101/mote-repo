# Franky’s Lab packages

Public compiled downloads for Mote, Mote Atlas and Mote Darwin on rootless iOS 16.
Source code is maintained in separate private repositories.

Add this source in Sileo: https://frankyfurt101.github.io/mote-repo/

- **Mote 0.1.2-1**: original 668-neuron creature. Launch confirmed on the XR.
- **Mote Atlas 0.1.0-1**: separate app with the whole proofread FlyWire v783
  graph (139,255 neurons, 54,492,922 represented synapses), native Metal/CPU
  modes, activity map, sensory inputs and wiring experiments. About 75 MB to
  download and 206 MB installed. Creature display and GPU / Metal mode confirmed on the XR by Franky.
  Physical-device performance has not been measured.

- **Mote Darwin 0.1.1-1**: separate full-connectome evolution app. Sixteen
  candidates, 472 inherited neural parameters, food trials, saved champions and
  unfamiliar-map comparisons. Compiled Metal shaders, local training and colony
  export. Version 0.1.1 adds read-only USB status, logs and training history.
  About 75 MB download. Mac/simulator tests pass; XR diagnostics acceptance pending.

Refresh Sources and search for the app name. Each app installs separately.
All three install under /var/jb/Applications. Installer scripts register their own
icons with uicache; they do not reboot the phone or alter jailbreak files.

These are authored experiments using real connectivity, not validated animal
brain emulations or recovered memories. Mote’s curated data is CC BY-NC 4.0;
Atlas and Darwin connectivity releases are CC BY 4.0. See ATTRIBUTION.txt and
ATLAS-ATTRIBUTION.txt / DARWIN-ATTRIBUTION.txt for sources, transformations and annotation citations.
