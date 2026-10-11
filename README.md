# ZG ZoneEssentials

## English

Homes, warps, TPA, kits, jobs, shop, auctions, moderation and travel tools. Current protected pair: server 4.5.1 + client 4.5.1, Minecraft 1.20.1 / Forge 47.x.

### Installation

Install the labeled server JAR on the server and its compatible client JAR on players' clients. Both files belong to the same CurseForge project. The two version numbers may differ; follow the stated pair, never mix releases. Required server dependencies: **ZoneCore 2.1.0+, ZoneCrates 2.0.5+, ZoneEconomy 1.3.0+**. ZoneProtes 2.9.0+ is optional for base rollback. Check the dependency version range of the exact uploaded file before installation.

### Configuration

Edit generated TOML files while the server or game is stopped unless a documented reload command is available. Back up persistent data before updates.

| Config file | Use |
|---|---|
| `config/zoneessentials-common.toml` | Homes, teleport, RTP, queues, cooldowns and command aliases. |
| `config/ZONEMODS/zoneessentials/jobs/trabajos.toml` | Job catalogue, permissions and rewards. |
| `config/ZONEMODS/zoneessentials/kits/kits.toml` | Kits and claim settings. |
| `config/ZONEMODS/zoneessentials/shop/catalogo.toml` | Shop items and prices. |
| `config/ZONEMODS/zoneessentials/subastas/ajustes.toml` | Auction limits and charges. |

See [configuration reference](CONFIGURATION.md) for keys detected in source and [release compatibility](RELEASES.md) for version-pair rules.

## Español

Homes, warps, TPA, kits, trabajos, tienda, subastas, moderación y viajes. Pareja protegida: servidor 4.5.1 + cliente 4.5.1, Minecraft 1.20.1 / Forge 47.x.

### Instalación

Instala el JAR marcado servidor en el servidor y su JAR cliente compatible en los clientes. Ambos archivos pertenecen al mismo proyecto CurseForge. Los números de versión pueden diferir; respeta la pareja indicada y no mezcles entregas. Dependencias de servidor: **ZoneCore 2.1.0+, ZoneCrates 2.0.5+, ZoneEconomy 1.3.0+**. ZoneProtes 2.9.0+ es opcional para restauración de bases. Comprueba el rango de versión del archivo exacto que instales.

### Configuración

Edita los TOML generados con el servidor o juego detenido, salvo que exista un comando de recarga documentado. Respalda los datos persistentes antes de actualizar.

| Archivo de configuración | Uso |
|---|---|
| `config/zoneessentials-common.toml` | Homes, teletransporte, RTP, colas, esperas y alias. |
| `config/ZONEMODS/zoneessentials/jobs/trabajos.toml` | Catálogo de trabajos, permisos y recompensas. |
| `config/ZONEMODS/zoneessentials/kits/kits.toml` | Kits y condiciones de reclamación. |
| `config/ZONEMODS/zoneessentials/shop/catalogo.toml` | Artículos y precios de tienda. |
| `config/ZONEMODS/zoneessentials/subastas/ajustes.toml` | Límites y cargos de subastas. |

Consulta la [referencia de configuración](CONFIGURATION.md) para claves detectadas en el código y la [compatibilidad de entregas](RELEASES.md) para las parejas de versiones.

## Ownership / Titularidad

Documentation and original ZONE visual assets © Elgochogms. This repository contains documentation and a project avatar only; it does not distribute mod source code, private mappings, server secrets or production configuration.

