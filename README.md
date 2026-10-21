# X-Wing Reference Artwork

This repository collects the X-Wing reference artwork used by Star Wars: Tabletop Commander.

## Contents

- `images/maneuvers/1.0/` — First Edition maneuver reference images, one file per ship type.
- `images/dials/1.0/` — First Edition printed maneuver dial images. These are separate from maneuver reference charts.
- `images/dials/2.0/` — Second Edition printed maneuver dial images. These are separate from maneuver reference charts.
- `images/tokens/1.0/` — First Edition token and token-reference artwork available from the upstream X-Wing data repository.
- `images/tokens/2.0/` — Second Edition token artwork. Keep this separate because several token names and designs changed between editions.
- `images/ship-tokens/1.0/` — First Edition pilot and ship cardboard token artwork.
- `images/ship-tokens/2.0/` — Second Edition pilot and ship cardboard token artwork.
- `metadata/manifest.json` — machine-readable locations for importers.

The maneuver files use the naming convention `xwing-1.0-<ship-slug>-maneuver.png`.

## Source and rights

The image files were obtained from the community [xwing-data repository](https://github.com/guidokessels/xwing-data). Star Wars names, artwork, symbols, and game content remain the property of their respective rights holders. This repository is an unmodified reference-artwork mirror for personal and community tool use. Review the upstream repository license and rights notices before redistributing or publishing a public mirror.

## Adding more artwork

Place Second Edition maneuver images in `images/maneuvers/2.0/`, printed dial images in the matching `images/dials/<edition>/` folder, status/token images in `images/tokens/<edition>/`, and pilot/ship cardboard images in `images/ship-tokens/<edition>/`. Keep filenames lowercase, stable, and descriptive, and update `metadata/manifest.json` when adding a new edition.
