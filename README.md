# 🗺️ LevelRange — OctoWoW

A lightweight World Map enhancement for **World of Warcraft 1.12**, adapted and maintained for **OctoWoW**.

LevelRange adds useful leveling information directly to the World Map, including **zone level ranges, faction status, dungeons, raids and fishing skill requirements**.

> This fork includes support for OctoWoW zones, dungeons and raids while preserving the original LevelRange experience.

## 📦 Installation

1. Download the addon.
2. Make sure the addon folder is named `LevelRange-Octo`.
3. Copy it to:

   `World of Warcraft\Interface\AddOns\LevelRange-Octo`

4. Restart the game.
5. Make sure **LevelRange** is enabled in the AddOns menu.

Open the World Map and move your cursor over a zone to display its LevelRange information.

## ✨ Features

- Displays recommended **zone level ranges** on the World Map.
- Shows whether a zone is:
  - Alliance
  - Horde
  - Contested
- Displays available **dungeons** and their recommended level ranges.
- Displays available **raids**.
- Shows minimum **Fishing skill requirements** where available.
- Dedicated in-game options window.
- Individual toggles for:
  - Level ranges
  - Dungeons
  - Raids
  - PvP diplomacy
  - Fishing requirements
- Support for original Vanilla zones and instances.
- Additional OctoWoW zones, dungeons and raids.
- FlightMap-compatible tooltip positioning.
- Lightweight and designed specifically for the World Map.

## 🐙 OctoWoW support

The addon includes additional content for the OctoWoW environment, including zones such as:

- Thalassian Highlands
- Blackstone Island
- Gilneas
- Gillijim's Isle
- Lapidis Isle
- Tel'Abim
- Scarlet Enclave
- Hyjal
- Grim Reaches
- Northwind
- Balor
- Moonwhisper Coast

It also includes custom OctoWoW dungeons and raids such as:

- The Crescent Grove
- Gilneas City
- Hateforge Quarry
- Karazhan Crypt
- Stormwind Vault
- Caverns of Time: The Black Morass
- Stormwrought Ruins
- Dragonmaw Retreat
- Windhorn Canyon
- Frostmane Hollow
- Emerald Sanctum
- Lower Karazhan Halls
- Timbermaw Hold

## ⚙️ Commands

| Command | Description |
|---|---|
| `/lr` | Open the LevelRange options window |
| `/levelrange` | Long version of `/lr` |
| `/lr toggle` | Toggle the LevelRange tooltip |
| `/lr instances` | Toggle dungeon information |
| `/lr pvp` | Toggle PvP diplomacy information |
| `/lr fishing` | Toggle fishing skill requirements |

Additional settings, including raid display, are available through the options window.

## 🌍 Localization

LevelRange includes localization support for:

- English
- French
- German
- Spanish
- Portuguese
- Chinese

## 🔧 Compatibility

- World of Warcraft 1.12
- Interface version `11200`
- OctoWoW
- FlightMap-compatible
- No myAddOns dependency required

## 📜 Version

Current version:

**2.3.1**

### 2.3.1

- Fixed the `/lr` options window.
- Removed the requirement for the `myAddOns` addon.

### 2.3.0

- Added Moonwhisper Coast.
- Added Windhorn Canyon.
- Added Frostmane Hollow.
- Added Timbermaw Hold.

The complete historical changelog remains available in [`Readme.txt`](Readme.txt).

## 📜 Project identity & licensing

LevelRange-Octo is an independent community-maintained fork with this known
GitHub ancestry:

- [Tenyar97/LevelRange-Turtle](https://github.com/Tenyar97/LevelRange-Turtle)
- [Spartelfant/LevelRange-Turtle](https://github.com/Spartelfant/LevelRange-Turtle)
- this maintained fork

The original LevelRange source by **Philip Hughes (Bull3t)** contains an
explicit license granting unlimited permission to use, reproduce and copy the
work, subject to accepting responsibility and liability for damage arising
from use.

Compatibility with **World of Warcraft**, **Turtle WoW**, **OctoWoW** or
**FlightMap** does not imply affiliation, endorsement or sponsorship.

For details, see:

- [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)
- [PROJECT_IDENTITY.md](PROJECT_IDENTITY.md)
- [Docs/CODE_PROVENANCE.md](Docs/CODE_PROVENANCE.md)
- [LICENSES/](LICENSES/)

## 🙏 Credits

Original **LevelRange** addon by **Bull3t**.

Additional development and maintenance by:

- Tenyar97
- rado-boy
- blehz
- rafacc87
- Diginfotek
- Spartelfant

OctoWoW adaptation and maintenance by **Dusk-92**.

Thanks to **Dhask** for allowing the use of FlightMap-related compatibility work.
