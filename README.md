# TikiTiki

Datos del server TikiTiki: modpack, skins por defecto y configuración compartida.

Server de Cobblemon para jugar entre amigos, en Minecraft **1.20.1** con **Forge 47.4.10**.

## Contenido

| Archivo | Qué tiene |
|---|---|
| `launcher.json` | Versión de Minecraft, loader, lista de mods con su hash SHA-1 y skins por defecto |
| `catalog.json` | Mods que subieron los jugadores y no están en Modrinth |
| `version.json` | Última versión publicada y hash de cada descarga |
| `servers/` | Un archivo JSON por server registrado |
| `skins/` | Skins por defecto, en modelo clásico y fino |
| `server/icon.png` | Ícono que aparece en la lista de Multijugador |

Los `.jar` no se guardan en el repo. Cada mod de la lista apunta a su descarga oficial en Modrinth y se verifica con su SHA-1.

## Mods

49 mods.

| Mod | Dónde va |
|---|---|
| [AmbientSounds](https://modrinth.com/mod/fM515JnW) | Solo cliente |
| [Architectury API](https://modrinth.com/mod/lhGA9TYQ) | Cliente y server |
| [Artifacts](https://modrinth.com/mod/P0Mu4wcQ) | Cliente y server |
| [Balm](https://modrinth.com/mod/MBAkmtvl) | Cliente y server |
| [Better Third Person](https://modrinth.com/mod/G1s2WpNo) | Solo cliente |
| [Better Villages](https://modrinth.com/mod/dGVX5JbJ) | Solo server |
| [Bushier Flowers](https://modrinth.com/mod/OK421ZCh) | Cliente y server |
| [Cave Dust](https://modrinth.com/mod/jawg7zT1) | Solo cliente |
| [Cloth Config API](https://modrinth.com/mod/9s6osm5g) | Cliente y server |
| [Cobblemon](https://modrinth.com/mod/MdwFAVRL) | Cliente y server |
| [CoroUtil](https://modrinth.com/mod/rLLJ1OZM) | Cliente y server |
| [CreativeCore](https://modrinth.com/mod/OsZiaDHq) | Cliente y server |
| [Curios API](https://modrinth.com/mod/vvuO3ImH) | Cliente y server |
| [CustomSkinLoader](https://modrinth.com/mod/idMHQ4n2) | Solo cliente |
| [Easy Anvils](https://modrinth.com/mod/OZBR5JT5) | Cliente y server |
| [Easy Magic](https://modrinth.com/mod/9hx3AbJM) | Cliente y server |
| [Eating Animations](https://modrinth.com/mod/X8CISwXp) | Solo cliente |
| [Falling Leaves (NeoForge/Forge)](https://modrinth.com/mod/2JAUNCL4) | Solo cliente |
| [Farmer's Delight](https://modrinth.com/mod/R2OftAxM) | Cliente y server |
| [GlitchCore](https://modrinth.com/mod/s3dmwKy5) | Cliente y server |
| [GraveStone Mod](https://modrinth.com/mod/RYtXKJPr) | Cliente y server |
| [GroovyModLoader (GML)](https://modrinth.com/mod/zg2tT2Vu) | Cliente y server |
| [Iron Chests](https://modrinth.com/mod/P3iIrPH3) | Cliente y server |
| [It Takes a Pillage](https://modrinth.com/mod/pe7FN3d6) | Cliente y server |
| [ItemPhysic](https://modrinth.com/mod/aT8BzaOj) | Cliente y server |
| [Jade 🔍](https://modrinth.com/mod/nvQzSEkH) | Cliente y server |
| [JamLib](https://modrinth.com/mod/IYY9Siz8) | Cliente y server |
| [Just Enough Items (JEI)](https://modrinth.com/mod/u6dRKJwZ) | Cliente y server |
| [Kotlin for Forge](https://modrinth.com/mod/ordsPcFz) | Cliente y server |
| [Library Ferret](https://modrinth.com/mod/DOB2l4oJ) | Cliente y server |
| [Moog's Structure Lib (moogs_structures)](https://modrinth.com/mod/1oUDhxuy) | Solo server |
| [Moonlight Lib](https://modrinth.com/mod/twkfQtEc) | Cliente y server |
| [More Mob Variants](https://modrinth.com/mod/JiEhJ3WG) | Cliente y server |
| [MVS - Moog's Voyager Structures](https://modrinth.com/mod/OQAgZMH1) | Solo server |
| [Neko's Enchanted Books](https://modrinth.com/mod/VZWuyRVr) | Solo cliente |
| [Not Enough Animations](https://modrinth.com/mod/MPCX6s5C) | Solo cliente |
| [Presence Footsteps [FORGE]](https://modrinth.com/mod/dLfueQtY) | Solo cliente |
| [Pretty Rain](https://modrinth.com/mod/IhZuHxkl) | Solo cliente |
| [Puzzles Lib](https://modrinth.com/mod/QAGBst4M) | Cliente y server |
| [Quark](https://modrinth.com/mod/qnQsVE2z) | Cliente y server |
| [RightClickHarvest](https://modrinth.com/mod/Cnejf5xM) | Solo server |
| [Serene Seasons](https://modrinth.com/mod/e0bNACJD) | Cliente y server |
| [Sophisticated Backpacks](https://modrinth.com/mod/TyCTlI4b) | Cliente y server |
| [Sophisticated Core](https://modrinth.com/mod/nmoqTijg) | Cliente y server |
| [Visual Workbench](https://modrinth.com/mod/kfqD1JRw) | Cliente y server |
| [Visuality: Reforged](https://modrinth.com/mod/z13R7Et1) | Solo cliente |
| [Waystones](https://modrinth.com/mod/LOpKHB2A) | Cliente y server |
| [What Are They Up To (Watut)](https://modrinth.com/mod/AtB5mHky) | Cliente y server |
| [Xaero's Minimap](https://modrinth.com/mod/1bokaNcj) | Cliente y server |
| [Zeta](https://modrinth.com/mod/MVARlG2f) | Cliente y server |

## Instalar a mano

1. Instala Minecraft 1.20.1 con Forge 47.4.10.
2. Baja los mods de la tabla. Los que dicen "Solo server" no hacen falta en el cliente.
3. Copia los `.jar` a la carpeta `mods` de tu instancia.

## Créditos

Cada mod pertenece a sus autores y se descarga desde su página en Modrinth. Las skins de `skins/` son las skins por defecto de Minecraft, propiedad de Mojang.
