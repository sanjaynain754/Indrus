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

The Actors/Heroes section contains male and female hero looks organized by gender and visual tier. Ilyra Senn (CHR-H-F-0012 / OUT-0038), in her original Boneglass Eclipse look, is cataloged in Heroes as requested. One attempted four-image hero generation had one credit-related failure; the failed image was not assigned an ID. The imported series lineup includes suit names, character names, and outfit IDs for lookup. Six additional character renders have also been numbered and placed in the Heroes section as requested. The villain lineup now contains ten cataloged looks: Kian Varek (CHR-V-M-0001 / OUT-0008), Vera Sorn (CHR-V-F-0001 / OUT-0009), Orvan Kest (CHR-V-M-0002 / OUT-0012), Varkesh Dhoom (CHR-V-M-0003 / OUT-0039), Nhal-Kor (CHR-V-M-0004 / OUT-0041), Keryth Voss (CHR-V-M-0005 / OUT-0042), Moruq Vaal (CHR-V-M-0006 / OUT-0043), Veyr Khal (CHR-V-M-0007 / OUT-0044), Nereth Vaal (CHR-V-F-0002 / OUT-0040), and Skelra Venn (CHR-V-F-0003 / OUT-0045). The newly added original portraits are stored in the matching Villains gender/tier folders with their IDs and outfit numbers in the filenames. All image paths are relative to this folder, so the package can be imported as a unit.

## Imported series lineup

The newly imported series actors/heroes are stored under `Heroes/Male/` and `Heroes/Female/`. Each image filename contains the character ID, outfit ID, character name, and the catalog records the separate `suit_name` field.

Primary sealed technology suit: **S-09 / Helix Prime Suit / Kabir Voss**.
