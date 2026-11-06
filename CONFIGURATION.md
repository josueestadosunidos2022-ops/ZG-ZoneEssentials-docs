# ZoneEssentials — Configuration / Configuración (2026-11-06)

| Side / Lado | Version / Versión |
|---|---|
| Server / Servidor | 4.5.13 |
| Client / Cliente | 4.5.13 |

## Current files / Archivos actuales

All existing paths and permissions remain in use. Preserve your configuration. / Se conservan rutas y permisos; guarda tus configuraciones.

| File / Archivo | Purpose / Uso |
|---|---|
| `config/ZONEMODS/zoneessentials/kits/kits.toml` | Kits and descriptions / Kits y descripciones |
| `config/ZONEMODS/zoneessentials/shop/catalogo.toml` | Shop products / Productos de tienda |
| `config/ZONEMODS/zoneessentials/subastas/ajustes.toml` | Auction settings / Ajustes de subastas |
| `config/ZONEMODS/zoneessentials/jobs/trabajos.toml` | Jobs and optional LevelUp XP / Trabajos y XP opcional |
| `config/ZONEMODS/zoneessentials/mensajes/automaticos.toml` | Automatic announcements / Anuncios automáticos |
| `config/ZONEMODS/zoneessentials/staff/inventarios.toml` | Staff inventory settings / Gestión de inventarios |
| `config/ZONEMODS/zoneessentials/staff/helpop.toml` | Help requests / Ayuda |
| `config/zoneessentials-common.toml` | Shared utility settings / Ajustes generales |
| `config/zoneessentials-baserollback.toml` | Rollback settings / Ajustes de restauración |

## Jobs → LevelUp

Place root `xp_zonelevelup_por_accion = 10` before the first `[[trabajo]]` in `trabajos.toml`. Zero disables it; an absent key defaults to 10 without replacing custom jobs. `/jobs estado` shows integration status and base XP. `/jobs reload` retains `zoneessentials.jobs.admin`. / La clave raíz va antes del primer trabajo; cero desactiva, ausencia usa 10 conservando trabajos. Los comandos muestran estado y recargan con su permiso actual.

The award is base LevelUp RPG XP once per paid action, even if several active jobs match. It is separate from coins and job XP and respects existing limits. Frozen players do not receive queued job rewards. / Es XP RPG base una vez por acción pagada aunque coincidan trabajos. Se separa de monedas y XP del oficio y respeta límites. Un jugador congelado no cobra eventos pendientes.

## Reload / Recarga

`/zoneessentials reload` reports each section. Accepted section names: `teletransportes`, `rangos`, `kits`, `shop`, `subastas`, `jobs`, `permisos`, `anuncios`. Each invalid loader retains its last valid configuration, while other valid sections can apply: this is not a single global transaction. / Cada apartado inválido conserva su configuración válida; los demás sí pueden aplicar. No es una transacción global.

`/zoneessentials diagnostico` reports configuration errors, kits, jobs, travel, LevelUp connection/base XP and announcement activation without changing inventory or money. / Diagnóstico administrativo sin modificar inventarios ni saldo.

Announcement `{online}` excludes vanished players. `CELESTE`, `VIOLETA` and `AZUL_OSCURO` are additional color aliases. Existing text and colors are retained. / El conteo excluye ocultos y añade esos alias, conservando mensajes y colores configurados.

[Current release / Entrega actual](RELEASE-2026-11-06.md) · [README](README.md).
