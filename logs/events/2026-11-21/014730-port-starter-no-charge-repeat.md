# Port Starter: not charging for 100 h 1 min

**Sat 21 Nov 2026, 01:47:30**

Still not charging: Port Starter has not reached 13.1 V for 100 h 1 min (since 2026-11-16 21:46). Now 12.51 V.
Check shore power, that the charger is on, and its output to this battery (fuse, switch, wiring).

## Battery

- **12.51 V** · 80% charge · Normal · 55 °F
- Last 2 hours: lowest 12.51 V, highest 12.52 V

## Victron Orion

- **Off** (Engine shutdown detected) · input 12.70 V
- Its input matches Port Starter (12.51 V).
- Its input matches Electronic Controls (12.67 V).

## Other batteries

- Starboard Starter: 13.26 V, 100%, Normal
- Electronic Controls: 12.67 V, 98%, Normal

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 03:55:21 | Bulk | 12.98 V |  |
| 03:55:24 | Off | 12.99 V | Engine shutdown detected |
| 06:33:09 | Off | 13.67 V |  |
| 06:33:17 | Bulk | 13.12 V |  |
| 10:31:32 | Bulk | 12.30 V |  |
| 10:31:35 | Off | 12.98 V | Engine shutdown detected |
| 13:04:56 | Off | 13.68 V |  |
| 13:05:03 | Bulk | 13.09 V |  |
| 17:02:42 | Bulk | 12.98 V |  |
| 17:02:44 | Off | 13.00 V | Engine shutdown detected |
| 19:37:33 | Off | 13.67 V |  |
| 19:37:40 | Bulk | 12.98 V |  |
| 23:35:52 | Bulk | 12.98 V |  |
| 23:35:54 | Off | 12.99 V | Engine shutdown detected |

## Data

- [Readings from the 2 hours before this alert](014730-port-starter-no-charge-repeat.csv) (CSV)
- [All readings for 2026-11-21](../../readings/2026-11-21/)

_Sent by your private Battery Monitor._
