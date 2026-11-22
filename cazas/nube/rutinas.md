# Rutinas de la nube

Creadas el 2026-11-14. El cron va con `CRON_TZ=America/Santiago`, así que la hora local se mantiene sola cuando
Chile cambia de horario (la columna UTC es la de hoy, con Chile en UTC-3). Environment: `env_015uRsYmvxKawqXTmyAKUFbE`
(Default, sin variables). Conector: solo Meta_Ads. Se administran en https://claude.ai/code/routines.

| Sesión | Id de la rutina | Cron | Hora local | UTC hoy | Modelo |
|---|---|---|---|---|---|
| BR | `trig_01GBWDEqv1a6nApwHyrvvmrR` | `CRON_TZ=America/Santiago 30 6,18 * * *` | 06:30 y 18:30 | 09:30 y 21:30 | claude-sonnet-5-5 |
| IT | `trig_015YykHJis1zySDmw8ZjkYm8` | `CRON_TZ=America/Santiago 35 6,18 * * *` | 06:35 y 18:35 | 09:35 y 21:35 | claude-sonnet-5-5 |
| FR | `trig_01Kc3c7zs4fDkjmMpKfthBBc` | `CRON_TZ=America/Santiago 40 6,18 * * *` | 06:40 y 18:40 | 09:40 y 21:40 | claude-sonnet-5-5 |
| RO | `trig_01KTkJ2wcHpkHMiBqDNyAVC6` | `CRON_TZ=America/Santiago 45 6,18 * * *` | 06:45 y 18:45 | 09:45 y 21:45 | claude-sonnet-5-5 |
| MX | `trig_01DSkUJ5mz9maUvDsHTm45jN` | `CRON_TZ=America/Santiago 50 6,18 * * *` | 06:50 y 18:50 | 09:50 y 21:50 | claude-sonnet-5-5 |
| CO | `trig_015ro3cUXyYmhw28uMWmAnLY` | `CRON_TZ=America/Santiago 55 6,18 * * *` | 06:55 y 18:55 | 09:55 y 21:55 | claude-sonnet-5-5 |
| EU | `trig_01NdbgTw9Q1DMEgbsLVR37tn` | `CRON_TZ=America/Santiago 25 6,18 * * *` | 06:25 y 18:25 | 09:25 y 21:25 | claude-sonnet-5-5 |

MX y CO se agregaron el 2026-11-15, como mercados **fuente**: lo que encuentran se lleva a BR, PT, IT, FR o RO.
EU (Estados Unidos, `countries: ["US"]`) se agregó el 2026-11-22, como **destino y fuente**. Desde el mismo día corre igual que las demás (dos veces, sonnet, esfuerzo medio, mismas herramientas), 5 minutos antes que BR.
