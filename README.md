# ExtraGear

[![Java CI](https://github.com/mybezo/ExtraGear/actions/workflows/maven.yml/badge.svg)](https://github.com/mybezo/ExtraGear/actions/workflows/maven.yml)
[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
[![Discord](https://img.shields.io/discord/565557184348422174?color=7289DA&label=Discord&logo=discord&logoColor=white)](https://discord.gg/fsD4Bkh)

ExtraGear is one of the oldest [Slimefun](https://github.com/Slimefun/Slimefun4) addons in existence.
It keeps things simple: it adds new **swords** and **armor sets** made from Slimefun's ingots and alloys,
and every piece comes with its own **enchantments**.

## Table of Contents
- [Requirements](#requirements)
- [Download](#download)
- [Installation](#installation)
- [Content](#content)
- [Configuration](#configuration)
- [Building from source](#building-from-source)
- [Discord](#discord)
- [License](#license)

## Requirements
| Dependency | Version |
| ---------- | ------- |
| Server     | Spigot / Paper 1.16.5 or newer |
| Java       | 8 or newer (match what your server requires) |
| Slimefun   | RC-27 or newer |

## Download
Development builds of the original addon are available on the
[Slimefun build server](https://thebusybiscuit.github.io/builds/TheBusyBiscuit/ExtraGear/master/).

<p align="center">
  <a href="https://thebusybiscuit.github.io/builds/TheBusyBiscuit/ExtraGear/master/">
    <img src="https://thebusybiscuit.github.io/builds/TheBusyBiscuit/ExtraGear/master/badge.svg" alt="Build Server"/>
  </a>
</p>

You can also [build it yourself](#building-from-source).

## Installation
1. Install [Slimefun](https://github.com/Slimefun/Slimefun4) on your server.
2. Put the ExtraGear `.jar` file into your server's `plugins` folder.
3. Restart the server. All items appear in the **ExtraGear** category of the Slimefun Guide.

## Content
All items are unlocked through Slimefun research:
swords cost **3 levels**, armor sets cost **5 levels**.

### Swords
Crafted in the **Enhanced Crafting Table**: two ingots on top of a stick, like a vanilla sword.

| Material | Enchantments |
| -------- | ------------ |
| Copper | Smite II |
| Tin | Sharpness I |
| Silver | Sharpness II |
| Aluminum | Bane of Arthropods III |
| Lead | Sharpness III, Unbreaking VIII |
| Zinc | Sharpness II |
| Magnesium | Sharpness II, Unbreaking V |
| Steel | Sharpness V, Unbreaking VI |
| Bronze | Sharpness III, Unbreaking VI |
| Duralumin | Sharpness III, Unbreaking VI |
| Billon | Sharpness IV, Unbreaking V |
| Brass | Smite IV, Unbreaking VI |
| Aluminum Brass | Bane of Arthropods IV, Unbreaking IV |
| Aluminum Bronze | Bane of Arthropods IV, Unbreaking V |
| Corinthian Bronze | Sharpness V, Unbreaking V |
| Solder | Sharpness IV, Unbreaking VI |
| Damascus Steel | Sharpness VI, Unbreaking VII |
| Hardened Metal | Sharpness VII, Unbreaking X |
| Reinforced Alloy | Sharpness VIII, Unbreaking VIII |
| Ferrosilicon | Smite VIII, Unbreaking IV |
| Gilded Iron *(golden sword)* | Bane of Arthropods VIII, Unbreaking X |
| Nickel | Sharpness VI, Unbreaking V |
| Cobalt | Sharpness VII, Unbreaking VII |

### Armor sets
Crafted in the **Armor Forge** with the vanilla armor shapes (helmet, chestplate, leggings and boots).
Every piece of a set has the same enchantments.

| Material | Base armor | Enchantments |
| -------- | ---------- | ------------ |
| Copper | Leather | Blast Protection II |
| Tin | Iron | Blast Protection III |
| Silver | Iron | Protection II |
| Aluminum | Iron | Blast Protection II, Unbreaking II |
| Lead | Iron | Protection III, Unbreaking VIII |
| Zinc | Iron | Protection III |
| Magnesium | Iron | Protection II, Unbreaking V |
| Steel | Iron | Protection III, Unbreaking IV |
| Cobalt | Iron | Protection VII, Unbreaking VII |

## Configuration
`plugins/ExtraGear/config.yml`:

```yaml
options:
  # Automatically download new development builds (only for "DEV - " builds)
  auto-update: false
```

## Building from source
You need JDK 8 or newer and [Maven](https://maven.apache.org/).

```bash
git clone https://github.com/mybezo/ExtraGear.git
cd ExtraGear
mvn clean package
```

The compiled jar is placed in the `target` folder.

## Discord
You can find Slimefun's community on Discord!
Click the badge below to join the server for suggestions, questions or other discussions about this addon.

<p align="center">
  <a href="https://discord.gg/fsD4Bkh">
    <img src="https://img.shields.io/discord/565557184348422174?color=7289DA&label=Discord&style=for-the-badge" alt="Discord Invite"/>
  </a>
</p>

Found a bug? Please open an [issue](https://github.com/mybezo/ExtraGear/issues).

## License
This project is open source and licensed under the [GPL-3.0 License](LICENSE).
ExtraGear was originally created by [TheBusyBiscuit](https://github.com/TheBusyBiscuit/ExtraGear).
