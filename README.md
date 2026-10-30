# X-Wing Maneuver Reference Artwork

Printable maneuver reference artwork for **Star Wars: X-Wing Miniatures Game** First Edition (1.0) and Second Edition (2.0).

Repository: https://github.com/rpsincorporated-ship-it/xwing-maneuver-reference-artwork

## What is included

- First Edition ship maneuver references
- Second Edition ship maneuver references
- Huge-ship maneuver references where applicable
- Separate edition folders and stable filenames
- PNG artwork suitable for digital viewing and printing
- Import-ready folder layout for compatible tabletop companion applications

Maneuver dial images, tokens, ship cardboard, and card artwork are intentionally excluded from this repository. The Syliure-class hyperspace ring is excluded because it does not have a maneuver table.

## Folder structure

```text
images/
└─ maneuvers/
   ├─ 1.0/
   └─ 2.0/
metadata/
└─ manifest.json
```

## Filename format

Files use lowercase, hyphen-separated names:

```text
xwing-1.0-tie-reaper-maneuver.png
xwing-1.0-gozanti-class-cruiser-maneuver.png
xwing-2.0-tie-reaper-maneuver.png
xwing-2.0-hmp-droid-gunship-maneuver.png
```

Avoid spaces, apostrophes, parentheses, and special characters in new filenames.

## Importing the artwork

Applications that support GitHub maneuver imports should use:

```text
images/maneuvers/1.0/
images/maneuvers/2.0/
```

PNG is preferred because it preserves maneuver colors and prints clearly. The repository contains visual references; structured maneuver values should be imported from the application's normal X-Wing data source.

## Accuracy and edition notes

Always confirm the edition before using a reference. First Edition huge ships may include energy changes associated with maneuvers. Ships with separate fore and aft sections have separate reference images where required.

## Copyright and licensing

This is a fan-created reference project and is not affiliated with or endorsed by Lucasfilm Ltd., Atomic Mass Games, Fantasy Flight Games, or any other rights holder.

Star Wars names, game content, ship designs, artwork, and trademarks remain the property of their respective owners. Contributors must verify that they have permission to upload, print, or redistribute any artwork. Please document the source and license for any new files.
