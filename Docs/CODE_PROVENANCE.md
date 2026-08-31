# LevelRange-Octo code provenance

Audit date: 2026-08-31

## Historical origin

The current source retains the original LevelRange header:

- Copyright (c) 2006 Philip Hughes (Bull3t)
- explicit unlimited permission to use, reproduce and copy the work, subject to
  the user accepting responsibility and liability for damage arising from use

The historical changelog in `Readme.txt` preserves the development history.

## GitHub fork chain

GitHub repository metadata confirms:

`Tenyar97/LevelRange-Turtle`
→ `Spartelfant/LevelRange-Turtle`
→ `Dusk-92/LevelRange-Octo`

## Immediate upstream comparison

Immediate upstream:

- https://github.com/Spartelfant/LevelRange-Turtle

At the time of this audit, the following current files are byte-identical at Git
blob level to the immediate upstream:

| File | Git blob SHA-1 |
| --- | --- |
| `LevelRange.xml` | `2d6bb8056f840b12c2df20f118f10d3c629f907b` |
| `Locale/LevelRange-chZN.lua` | `4f0e1830ca91acd7fed546a01f60632391b43a8d` |
| `Locale/LevelRange-deDE.lua` | `cfeb0c6b47b857fdae665bef05f69416bc92cf76` |
| `Locale/LevelRange-esES.lua` | `c7a511d7c40858c429e519d179dd1b00f199ee87` |
| `Locale/LevelRange-frFR.lua` | `5c199db97b284a4ae39e470d57002b3729ce3c33` |
| `Locale/LevelRange-ptBR.lua` | `35f79d97d3b9d13c51505b122af9c25b4443ef7a` |

The English locale, main Lua file, TOC, installation text and changelog contain
later LevelRange-Octo changes and therefore are not represented as exact
upstream matches.

## Dusk-92 maintenance

The changelog records Dusk-92 maintenance including:

### 2.3.0

- Moonwhisper Coast
- Windhorn Canyon
- Frostmane Hollow
- Timbermaw Hold

### 2.3.1

- fixed the `/lr` options window
- removed the practical requirement for the myAddOns addon

Git history remains the authoritative record for the exact implementation
changes.

## FlightMap provenance

The source has historically contained the credit:

"Thanks to Dhask for allowing the use of his FlightMap."

The current addon retains FlightMap-compatible tooltip positioning. This is
documented as historical permission/compatibility provenance rather than a
claim of ownership over FlightMap.

## Licensing boundary

The original source includes an explicit license grant, which is preserved
verbatim in `LICENSES/LevelRange-Original-License.txt`.

Later contributor rights are not erased by that historical notice. Attribution
for later maintainers remains preserved in the README, TOC and changelog.
