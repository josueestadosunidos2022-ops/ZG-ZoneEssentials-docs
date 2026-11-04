# ZoneEssentials

## Current build / Versión actual — 2026-11-03 revision 3

4.5.10

[Server](https://www.curseforge.com/minecraft/mc-mods/zoneessentials/files/9430598) · [Client](https://www.curseforge.com/minecraft/mc-mods/zoneessentials/files/9430560)

Both sides must use 4.5.10. /warp opens the permission-filtered scrolling interface; /warp name and saved destinations remain available. / Ambos lados 4.5.10; /warp abre la interfaz y conserva destinos, permisos y comando directo.

[English / Español installation and changes](RELEASE-2026-11-03-r3.md). Availability follows each file approval. / Disponibilidad según aprobación del archivo.

## Historical documentation / Documentación histórica

Versions below are earlier releases; the current build above takes precedence. / Las versiones siguientes son anteriores; prevalece la versión actual de arriba.

# ZoneEssentials 4.5.9

## English

Server utilities, travel, homes, kits, shops, auctions, economy integrations and staff tools. Version 4.5.9 adds a dated seven-day death history, item preview and confirmed recovery that preserves newer inventory items and prevents duplicate recovery. Staff flow: /staff > player > Muertes (7 días) > date > Ver objetos > reason > Recuperar twice. Keep world/data/zoneessentials_staff.dat and existing TOML. The matched 4.5.9 client/server pair is required.

## Español

Utilidades, viajes, hogares, kits, tiendas, subastas e interfaz de personal. 4.5.9 añade historial de muertes de siete días, selección por fecha, vista previa y recuperación confirmada que conserva objetos nuevos y evita duplicados. Flujo: /staff > jugador > Muertes (7 días) > fecha > Ver objetos > motivo > Recuperar dos veces. Conserva world/data/zoneessentials_staff.dat y tus TOML. Usa el par cliente/servidor 4.5.9.


| Side / Lado | Version | File |
|---|---|---|
| server | 4.5.9 | `zoneessentials-server-4.5.9-protected.jar` |
| client | 4.5.9 | `zoneessentials-client-4.5.9-protected.jar` |

## Dependencies / Dependencias

- **server**: zonecore: Required Dependency ([2.1.0,)); zonecrates: Required Dependency ([2.0.5,)); zoneeconomy: Required Dependency ([1.3.0,)); zonaprotes: Optional Dependency ([2.9.0,))
- **client**: No additional mod requirement / Sin requisitos adicionales

## Installation / Instalación

Install only the file for each side. Never mix two versions or both side distributions in one mods folder. Back up the world and preserve TOML/player data. Dedicated-server-only mods do not belong in a client modpack.

Instala solo el archivo del lado correspondiente. No mezcles versiones ni ambos JAR en una carpeta mods. Respalda mundo y conserva TOML/progreso. Los mods exclusivos de servidor no van en el modpack de cliente.

Protected public files retain features without distributing private source, mappings or production configuration/account data. File/resources/shared schemas and isolated server startup/clean save were checked; no new GUI/full-modpack or live multiplayer test was performed. File availability depends on CurseForge approval.

Los archivos públicos conservan funciones con protección, sin fuentes, mappings ni datos privados. Se verificaron archivos/esquemas y arranque/cierre local aislado; no una nueva prueba gráfica o multijugador real. Disponibilidad sujeta a aprobación de CurseForge.

## Ownership / Titularidad

Original ZONE code and artwork © Elgochogms. All Rights Reserved. Public documentation repository only; source and mappings remain private.
