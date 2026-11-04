# ZoneEssentials

## Current builds / Versiones actuales — 2026-11-04

| Side / Lado | Version / Versión | File / Archivo |
|---|---|---|
| server | 4.5.12 | [zoneessentials-server-4.5.12-protected.jar](https://www.curseforge.com/projects/1738040/files/9438654) |
| client | 4.5.11 | [zoneessentials-client-4.5.11-protected.jar](https://www.curseforge.com/projects/1738040/files/9438676) |

Minecraft 1.20.1 / Forge 47.4.x / Java 17. Protected public Beta builds; availability depends on each file approval. / Betas públicas protegidas; disponibilidad según aprobación de cada archivo.

## English — What is new

Includes the 4.5.11 blue/purple/cyan redesign of kits, shops, auctions, Jobs, warps, staff, death history and inventory inspection; kit editor has 54 content slots and preserves unseen overflow from older kits. SERVER 4.5.12 adds 10 configurable BASE ZoneLevelUp XP once per successfully paid Jobs action, outside the per-job loop, using optional PlayerLevels.award and real RPG multipliers/caps. Existing money/job XP rules remain; canceled/protected/unpaid actions give no bonus. Root xp_zonelevelup_por_accion=10 (0 disables, 0..10000) in jobs/trabajos.toml; /jobs reload and /jobs estado. CLIENT remains 4.5.11 and is compatible with server 4.5.12. LevelUp integration is optional.

## Español — Novedades

Incluye rework 4.5.11 azul/morado/celeste de kits, tiendas, subastas, Jobs, warps, staff, muertes e inventarios; editor de kits con 54 casillas que conserva excedente antiguo no visible. SERVIDOR 4.5.12 añade 10 XP BASE configurables de ZoneLevelUp una vez por acción de Jobs pagada, fuera del bucle de oficios, mediante PlayerLevels.award opcional y multiplicadores/topes reales. Mantiene monedas/XP oficio; acciones canceladas/protegidas/sin pago no dan bono. Clave raíz xp_zonelevelup_por_accion=10 (0 desactiva, 0..10000) en jobs/trabajos.toml; /jobs reload y /jobs estado. CLIENTE continúa 4.5.11, compatible con servidor 4.5.12. LevelUp opcional.

## Installation / Instalación

Use Essentials SERVER 4.5.12 with CLIENT 4.5.11. The Jobs XP integration requires LevelUp only if you want that optional feature. / Usa Essentials SERVIDOR 4.5.12 con CLIENTE 4.5.11; LevelUp solo para la función opcional de XP RPG.

Stop the affected instance, back up the world/config, remove only the previous same-mod/same-side JAR, and install the table version. Preserve character data, wallets and TOML. Do not put server-only dependencies on clients. / Detén la instancia, respalda mundo/config, sustituye solo el JAR anterior del mismo mod y lado, y conserva personajes, cartera y TOML. No instales dependencias exclusivas de servidor en el cliente.

## Dependencies / Dependencias

**server**: `zonecore` [2.1.0,) (required/obligatorio; BOTH); `zonecrates` [2.0.5,) (required/obligatorio; BOTH); `zoneeconomy` [1.3.0,) (required/obligatorio; SERVER); `zonaprotes` [2.9.0,) (optional/opcional; SERVER); `zonelevelup` [2.0.0-beta29,) (optional/opcional; SERVER).

**client**: No additional Zone requirement / Sin requisito Zone adicional.

[Full changes and usage / Novedades y uso](RELEASE-2026-11-04.md) · [Configuration / Configuración](CONFIGURATION.md) · [Historical releases / Entregas históricas](RELEASES.md).

## Validation / Verificación

Original release checks and isolated startup/command registration of the protected set were reviewed. Shared schemas: Essentials 35, Guardian 13 and Misions 4 classes, with no mapping differences. This does not certify a new graphical client session, two-player gameplay, full third-party modpack, hosting deployment or FPS/TPS. / Revisadas las verificaciones de entrega y el arranque/registro de comandos del conjunto protegido. Esquemas compartidos sin diferencias de mapeo: Essentials 35, Guardian 13 y Misions 4 clases. No certifica una nueva sesión gráfica, dos jugadores, modpack completo, hosting ni FPS/TPS.

## Ownership / Titularidad

Original ZONE code and visual assets © Elgochogms. Public documentation only: no mod sources, private obfuscation maps, credentials or production player data. Existing rights of earlier distributions are preserved.
