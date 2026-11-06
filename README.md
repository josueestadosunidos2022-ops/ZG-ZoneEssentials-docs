# ZoneEssentials

Server utilities for kits, shops, auctions, travel, jobs and staff management, with matching client interfaces.

Utilidades de servidor para kits, tiendas, subastas, viajes, trabajos y gestión de staff, con interfaces de cliente.

## Current release / Entrega actual — 2026-11-06

Minecraft **1.20.1**, Forge **47.x** (47.4.x for this release set), Java **17**. File availability follows CurseForge approval. / Disponibilidad de archivos según aprobación de CurseForge.

| Side / Lado | Version / Versión |
|---|---|
| Server / Servidor | 4.5.13 |
| Client / Cliente | 4.5.13 |

**Compatibility / Compatibilidad:** Use the 4.5.13 pair / Usar la pareja 4.5.13.

[Downloads / Descargas](https://www.curseforge.com/projects/1738040/files) · [Release guide / Guía de novedades](RELEASE-2026-11-06.md) · [Configuration / Configuración](CONFIGURATION.md)

## English — Requirements and quick start

Server: ZoneCore 2.1.0+, ZoneCrates 2.0.5+ and ZoneEconomy 1.3.0+; retain the currently compatible Economy beta8 setup. Protes 2.9.0+ and LevelUp beta29+ are optional integrations. The Essentials client does not require server-only Core.

Open `/kit`, `/shop`, `/ah` or `/warp`. Use `/zoneessentials viaje` to inspect your travel and `/tpcancel` to cancel it. Administrators use `/zoneessentials diagnostico` and `/zoneessentials reload <section>`.

### What changed

- Shop/AH forms retain edits through refresh and resize, validate catalog revisions and recover pending states without resending transactions.
- Kits avoid unchanged writes; warp scrolling recovers missing reads, and `/zoneessentials viaje` reports personal pending travel.
- Frozen players cannot trade through already-open screens. Reloads report each section, diagnostics expand, and public online counts hide vanished players.

## Español — Requisitos e inicio

Servidor: ZoneCore 2.1.0+, ZoneCrates 2.0.5+ y ZoneEconomy 1.3.0+; conserva la instalación compatible Economy beta8. Protes 2.9.0+ y LevelUp beta29+ son integraciones opcionales. El cliente Essentials no exige Core de servidor.

Abre `/kit`, `/shop`, `/ah` o `/warp`. Consulta tu viaje con `/zoneessentials viaje` y cancélalo con `/tpcancel`. Administración: `/zoneessentials diagnostico` y `/zoneessentials reload <apartado>`.

### Novedades

- Los formularios Shop/AH conservan campos al refrescar o redimensionar, validan revisiones y recuperan estado sin repetir transacciones.
- Kits evita escrituras sin cambios; warps recupera lecturas pendientes y `/zoneessentials viaje` muestra el viaje propio.
- Los congelados no comercian desde pantallas abiertas. Recargas por apartado, diagnóstico ampliado y conteo público que excluye vanish.

## Updating / Actualizar

Stop the affected instance, back up world/configuration, replace only the previous same-mod/same-side JAR and retain player data. Never install the dedicated and client JARs of one mod together. / Detén la instancia correspondiente, respalda mundo/configuración y sustituye solo el JAR del mismo mod y lado conservando datos. Nunca instales juntos los JAR dedicado y cliente del mismo mod.

## Validation scope / Alcance de verificación

The delivery records 487 checks: 250 isolated server, 184 regression, 27 integration with LevelUp r54/Core 2.1.5 and 26 real-screen/widget checks in Forge data mode. The latter do not open OpenGL. Full graphical and multiplayer modpack review remains pending.

La entrega registra 487 comprobaciones: 250 servidor aislado, 184 regresión, 27 integración con LevelUp r54/Core 2.1.5 y 26 de pantallas/widgets en modo datos Forge. Estas últimas no abren OpenGL. Sigue pendiente la revisión gráfica y multijugador del modpack.

## Rights / Derechos

Original ZONE code and assets © Elgochogms; existing licenses and third-party notices remain applicable. This repository provides public documentation. / Código y recursos originales ZONE © Elgochogms; se conservan licencias y avisos de terceros. Este repositorio contiene documentación pública.
