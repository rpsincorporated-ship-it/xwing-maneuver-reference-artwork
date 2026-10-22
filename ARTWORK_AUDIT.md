# X-Wing artwork audit

Audit date: 2026-10-21 (refreshed after faction-complete import)

## Maneuver and dial images

The repository currently contains 55 First Edition maneuver images.

### First Edition ship maneuver images still missing

- GR-75 Medium Transport — `xwing-1.0-gr-75-medium-transport-maneuver.png`

The other previously missing First Edition maneuver files are now present in
the repository, including the Resistance and First Order ship types.

Fore/Aft records above should eventually share one dial image per physical huge ship. The app already groups those records for display.

### Second Edition

No Second Edition maneuver images are currently present. The current Second Edition source contains 108 faction ship files, representing 89 unique ship files after removing faction duplicates. A complete image set should be added under `images/maneuvers/2.0/`, one image per unique ship type.

The unique Second Edition ship types currently requiring maneuver images are:

`A/SF-01 B-wing`, `Aggressor Assault Fighter`, `Alpha-class Star Wing`, `ARC-170 Starfighter`, `Attack Shuttle`, `Auzituck Gunship`, `Belbullab-22 Starfighter`, `BTA-NR2 Y-wing`, `BTL-A4 Y-wing`, `BTL-B Y-wing`, `BTL-S8 K-wing`, `C-ROC Cruiser`, `Clone Z-95 Headhunter`, `CR90 Corvette`, `Customized YT-1300`, `Delta-7 Aethersprite`, `Delta-7B Aethersprite`, `Droid Tri-Fighter`, `E-wing`, `Escape Craft`, `ETA-2 Actis`, `Fang Fighter`, `Fireball`, `Firespray-class Patrol Craft`, `G-1A Starfighter`, `Gauntlet Fighter`, `Gozanti-class Cruiser`, `GR-75 Medium Transport`, `HMP Droid Gunship`, `HWK-290`, `Hyena-class Droid Bomber`, `JumpMaster 5000`, `Kihraxz Fighter`, `LAAT/i Gunship`, `Lambda-class T-4A Shuttle`, `Lancer-class Pursuit Craft`, `M12-L Kimogila Fighter`, `M3-A Interceptor`, `MG-100 StarFortress SF-17`, `Modified TIE/ln Fighter`, `Modified YT-1300`, `N-1 Naboo Royal Starfighter`, `Nantex-class Starfighter`, `Nimbus-class V-wing`, `Quadrijet Transfer Spacetug`, `Raider-class Corvette`, `Resistance Transport`, `Resistance Transport Pod`, `Rogue-class Starfighter`, `RZ-1 A-wing`, `RZ-2 A-wing`, `Scavenged YT-1300`, `Scurrg H-6 Bomber`, `Sheathipede-class Shuttle`, `Sith Infiltrator`, `ST-70 Assault Ship`, `StarViper-class Attack Platform`, `Syliure-class Hyperspace Ring`, `T-65 X-wing`, `T-70 X-wing`, `TIE Advanced v1`, `TIE Advanced x1`, `TIE Aggressor`, `TIE/ba Interceptor`, `TIE/ca Punisher`, `TIE Defender`, `TIE/fo Fighter`, `TIE/in Interceptor`, `TIE/ln Fighter`, `TIE/ph Phantom`, `TIE/rb Heavy`, `TIE Reaper`, `TIE/sa Bomber`, `TIE/se Bomber`, `TIE/sf Fighter`, `TIE/vn Silencer`, `TIE/wi Whisper`, `Trident-class Assault Ship`, `Upsilon-class Command Shuttle`, `UT-60D U-wing`, `V-19 Torrent`, `VCX-100`, `VT-49 Decimator`, `Vulture-class Droid Fighter`, `Xi-class Light Shuttle`, `YT-2400`, `YV-666`, `Z-95 Headhunter`.

The TIE Reaper and TIE/sk Striker artwork filenames are explicitly tracked in
the downloadable checklist, including their maneuver, dial, and cardboard
token files.

### Dial images

Printed dial images are missing for **all First Edition and Second Edition ships**. These are separate from maneuver reference charts and should be stored under:

- `images/dials/1.0/`
- `images/dials/2.0/`

For split huge ships, store one physical dial image per ship type, not separate Fore/Aft copies.

## Token images

The repository currently has 12 upstream First Edition token/reference images in `images/tokens/1.0/`: bomb-token
sheets, debris cloud, ion, reload/jam, and tractor beam. These are reference
images and do not cover the complete token set for either edition.

### First Edition token and marker artwork still needed

- Focus
- Evade
- Blue Target Lock and Red Target Lock
- Stress
- Shield
- Weapons Disabled
- Ion (standalone token; the current IonToken image is a reference image)
- Tractor Beam (standalone token; the current image is a reference image)
- Jam (standalone token; the current image is part of a reference sheet)
- Cloak
- Reinforce
- Coordinate
- Energy
- Ordnance
- Charge and Force markers where used by First Edition epic or card content
- Bomb and obstacle token sheets beyond the currently mirrored files

### Second Edition token and marker artwork still needed

- Focus
- Evade
- Lock
- Stress
- Shield
- Calculate
- Force
- Charge
- Ion
- Tractor
- Jam
- Strain
- Deplete
- Disarm
- Cloak
- Reinforce
- Coordinate
- Boost
- Barrel Roll
- SLAM
- Reload
- Bomb and device tokens
- Gas cloud, debris cloud, and other obstacle tokens
- Energy and epic/huge-ship markers where used by conversion or epic content

The current app’s edition-specific tracker rules distinguish the First Edition
conditions `Stress`, `Ion`, `Tractor Beam`, `Weapons Disabled`, and `Jam` from
the Second Edition conditions `Stress`, `Ion`, `Tractor`, `Jam`, `Disarm`,
`Strain`, and `Deplete`. Artwork should preserve those edition labels rather
than treating them as interchangeable files.

Second Edition token artwork is not yet present in `images/tokens/2.0/`. The app can continue using its text/icon fallback until these files are added.

## Card image audit

Card images are supplied by the imported X-Wing data pack and its image URLs;
they are not stored in this maneuver-artwork repository. After importing all
factions, the app should still verify every ship, pilot, and upgrade record for
an image URL and report records without artwork. Missing card images cannot be
determined from this repository alone because they depend on the exact data
pack version and whether offline image download was selected during import.

## Pilot and ship cardboard tokens

Pilot/ship cardboard tokens are a separate category from maneuver charts,
printed dials, and status tokens. They are currently missing for both editions:

- First Edition pilot/ship cardboard tokens: add files under `images/ship-tokens/1.0/`.
- Second Edition pilot/ship cardboard tokens: add files under `images/ship-tokens/2.0/`.

The set should cover every ship type and every named pilot cardboard token that
the corresponding edition's data source defines. Split Fore/Aft huge ships by
their actual section cardboard, while keeping their maneuver dial artwork
separate and shared as documented above.

## Source note

Ship coverage was compared against the current `guidokessels/xwing-data` First Edition `data/ships.js` and the current `xwingtmg/xwing-data2` Second Edition `data/manifest.json`. Artwork remains subject to the upstream repository and Star Wars rights-holder terms.


