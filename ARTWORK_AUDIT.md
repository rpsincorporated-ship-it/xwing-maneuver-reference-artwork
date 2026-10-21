# X-Wing artwork audit

Audit date: 2026-10-21

## Maneuver and dial images

The repository currently contains 44 First Edition maneuver images.

### First Edition ship maneuver images still missing

- Auzituck Gunship — `xwing-1.0-auzituck-gunship-maneuver.png`
- C-ROC Cruiser — `xwing-1.0-c-roc-cruiser-maneuver.png`
- CR90 Corvette (Fore) — `xwing-1.0-cr90-corvette-fore-maneuver.png`
- CR90 Corvette (Aft) — `xwing-1.0-cr90-corvette-aft-maneuver.png`
- Gozanti-class Cruiser — `xwing-1.0-gozanti-class-cruiser-maneuver.png`
- GR-75 Medium Transport — `xwing-1.0-gr-75-medium-transport-maneuver.png`
- Raider-class Corvette (Fore) — `xwing-1.0-raider-class-corvette-fore-maneuver.png`
- Raider-class Corvette (Aft) — `xwing-1.0-raider-class-corvette-aft-maneuver.png`
- Scurrg H-6 Bomber — `xwing-1.0-scurrg-h-6-bomber-maneuver.png`
- TIE Aggressor — `xwing-1.0-tie-aggressor-maneuver.png`
- TIE Reaper — `xwing-1.0-tie-reaper-maneuver.png`
- Upsilon-class Shuttle — `xwing-1.0-upsilon-class-shuttle-maneuver.png`

Fore/Aft records above should eventually share one dial image per physical huge ship. The app already groups those records for display.

### Second Edition

No Second Edition maneuver images are currently present. The current Second Edition source contains 108 faction ship files, representing 89 unique ship files after removing faction duplicates. A complete image set should be added under `images/maneuvers/2.0/`, one image per unique ship type.

The unique Second Edition ship types currently requiring maneuver images are:

`A/SF-01 B-wing`, `Aggressor Assault Fighter`, `Alpha-class Star Wing`, `ARC-170 Starfighter`, `Attack Shuttle`, `Auzituck Gunship`, `Belbullab-22 Starfighter`, `BTA-NR2 Y-wing`, `BTL-A4 Y-wing`, `BTL-B Y-wing`, `BTL-S8 K-wing`, `C-ROC Cruiser`, `Clone Z-95 Headhunter`, `CR90 Corvette`, `Customized YT-1300`, `Delta-7 Aethersprite`, `Delta-7B Aethersprite`, `Droid Tri-Fighter`, `E-wing`, `Escape Craft`, `ETA-2 Actis`, `Fang Fighter`, `Fireball`, `Firespray-class Patrol Craft`, `G-1A Starfighter`, `Gauntlet Fighter`, `Gozanti-class Cruiser`, `GR-75 Medium Transport`, `HMP Droid Gunship`, `HWK-290`, `Hyena-class Droid Bomber`, `JumpMaster 5000`, `Kihraxz Fighter`, `LAAT/i Gunship`, `Lambda-class T-4A Shuttle`, `Lancer-class Pursuit Craft`, `M12-L Kimogila Fighter`, `M3-A Interceptor`, `MG-100 StarFortress SF-17`, `Modified TIE/ln Fighter`, `Modified YT-1300`, `N-1 Naboo Royal Starfighter`, `Nantex-class Starfighter`, `Nimbus-class V-wing`, `Quadrijet Transfer Spacetug`, `Raider-class Corvette`, `Resistance Transport`, `Resistance Transport Pod`, `Rogue-class Starfighter`, `RZ-1 A-wing`, `RZ-2 A-wing`, `Scavenged YT-1300`, `Scurrg H-6 Bomber`, `Sheathipede-class Shuttle`, `Sith Infiltrator`, `ST-70 Assault Ship`, `StarViper-class Attack Platform`, `Syliure-class Hyperspace Ring`, `T-65 X-wing`, `T-70 X-wing`, `TIE Advanced v1`, `TIE Advanced x1`, `TIE Aggressor`, `TIE/ba Interceptor`, `TIE/ca Punisher`, `TIE Defender`, `TIE/fo Fighter`, `TIE/in Interceptor`, `TIE/ln Fighter`, `TIE/ph Phantom`, `TIE/rb Heavy`, `TIE Reaper`, `TIE/sa Bomber`, `TIE/se Bomber`, `TIE/sf Fighter`, `TIE/vn Silencer`, `TIE/wi Whisper`, `Trident-class Assault Ship`, `Upsilon-class Command Shuttle`, `UT-60D U-wing`, `V-19 Torrent`, `VCX-100`, `VT-49 Decimator`, `Vulture-class Droid Fighter`, `Xi-class Light Shuttle`, `YT-2400`, `YV-666`, `Z-95 Headhunter`.

### Dial images

Printed dial images are missing for **all First Edition and Second Edition ships**. These are separate from maneuver reference charts and should be stored under:

- `images/dials/1.0/`
- `images/dials/2.0/`

For split huge ships, store one physical dial image per ship type, not separate Fore/Aft copies.

## Token images

The repository currently has 12 upstream token/reference images: bomb-token sheets, debris cloud, ion, reload/jam, and tractor beam.

The following commonly used X-Wing token/action images still need artwork files or a deliberately designed original icon set:

- Focus
- Evade
- Target Lock
- Stress
- Shield
- Weapons Disabled
- Energy
- Ordnance
- Charge
- Force
- Calculate
- Reinforce
- Coordinate
- Boost
- Barrel Roll
- Cloak
- SLAM
- Tractor Beam standalone token
- Jam standalone token
- Ion standalone token
- Strain
- Deplete
- Disarm
- Blue/green/red target-lock or charge states, if tracked separately

The current app can continue using its text/icon fallback until these files are added.

## Source note

Ship coverage was compared against the current `guidokessels/xwing-data` First Edition `data/ships.js` and the current `xwingtmg/xwing-data2` Second Edition `data/manifest.json`. Artwork remains subject to the upstream repository and Star Wars rights-holder terms.

