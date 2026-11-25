# Actors / Character Outfit Asset Library

This package contains the series actors/heroes character-face and outfit images, organized for later repository import. It stores visual assets and minimal lookup metadata only; it does not define biographies, abilities, skills, weapons, or story canon.

## Folder structure

```text
Heroes/
  Male/Premium-Look/
  Male/Standard-Look/
  Female/Premium-Look/
  Female/Standard-Look/
Villains/
  Male/Premium-Look/
  Male/Standard-Look/
  Female/Premium-Look/
  Female/Standard-Look/
catalog.json
catalog.csv
```

## IDs

- `CHR-H-M-####`: Hero, Male section.
- `CHR-H-F-####`: Hero, Female section.
- `CHR-V-M-####`: Villain, Male section.
- `CHR-V-F-####`: Villain, Female section.
- `OUT-####`: Unique outfit asset ID. The character ID and outfit ID are both included in the image filename and catalog files.

Generated character names are working labels only. They do not assign a nationality, personality, or backstory. Color names and meanings are creative design intentions for this catalog, not universal cultural meanings.

`Premium-Look` and `Standard-Look` classify visual complexity and finish only. They are not cost estimates; actual production costs require materials, labor, fittings, stunt versions, and local supplier quotes.

## Current inventory

The Actors/Heroes section contains male and female hero looks organized by gender and visual tier. One attempted four-image hero generation had one credit-related failure; the failed image was not assigned an ID. The imported series lineup includes suit names, character names, and outfit IDs for lookup. Six additional character renders have also been numbered and placed in the Heroes section as requested. The villain lineup includes Kian Varek (CHR-V-M-0001 / OUT-0008), Orvan Kest (CHR-V-M-0002 / OUT-0012), and Ilyra Senn (CHR-V-F-0002 / OUT-0038), whose Boneglass Eclipse Suit adds a pale ceramic and smoky-glass palette. The villain images are newly generated with original faces. All image paths are relative to this folder, so the package can be imported as a unit.

## Imported series lineup

The newly imported series actors/heroes are stored under `Heroes/Male/` and `Heroes/Female/`. Each image filename contains the character ID, outfit ID, character name, and the catalog records the separate `suit_name` field.

Primary sealed technology suit: **S-09 / Helix Prime Suit / Kabir Voss**.
