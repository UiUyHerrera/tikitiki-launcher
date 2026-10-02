# TikiTiki Server Configuration

Repositorio de contenido y configuración compartida del launcher del servidor TikiTiki, una comunidad de Minecraft con Cobblemon. Mantiene la configuración del juego, el catálogo de mods, los recursos del servidor y las skins predeterminadas.

[English version](#english)

## Configuración actual

- Minecraft 1.21.1.
- Fabric Loader 0.19.5.
- La lista de mods, versiones y hashes se define en launcher.json, que es la fuente de verdad para el launcher.

## Contenido del repositorio

- launcher.json: versión de Minecraft y loader, mods y configuración compartida del launcher.
- catalog.json: catálogo de mods aportados por jugadores que no están en Modrinth.
- version.json: versión publicada y hashes de las descargas.
- packs/: paquetes de recursos del servidor.
- server/: recursos del servidor, incluido server/icon.png.
- skins/: skins predeterminadas.

Los archivos de mods no se almacenan en el repositorio; la configuración apunta a las descargas correspondientes y permite verificar los archivos mediante sus hashes.

## Uso

Este repositorio sirve como fuente de datos para el launcher de TikiTiki. Para jugar, utiliza el launcher configurado para el servidor y mantén los archivos sincronizados con launcher.json. No cambies manualmente versiones o hashes sin actualizar y verificar la configuración asociada.

## English

Shared launcher content and configuration for the TikiTiki Minecraft server community featuring Cobblemon. It maintains game configuration, the mod catalog, server assets, and default skins.

### Current configuration

- Minecraft 1.21.1.
- Fabric Loader 0.19.5.
- The mod list, versions, and hashes are defined in launcher.json, the launcher's source of truth.

### Repository contents

- launcher.json: Minecraft and loader versions, mods, and shared launcher configuration.
- catalog.json: catalog of player-contributed mods that are not on Modrinth.
- version.json: published version and download hashes.
- packs/: server resource packs.
- server/: server assets, including server/icon.png.
- skins/: default skins.

Mod files are not stored in this repository; the configuration points to their downloads and allows files to be verified with hashes.

### Usage

This repository provides data for the TikiTiki launcher. To play, use the launcher configured for the server and keep files in sync with launcher.json. Do not change versions or hashes manually without updating and verifying the related configuration.
