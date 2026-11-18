# Starboard Starter: not charging for 10 h 0 min

**Wed 18 Nov 2026, 17:36:26**

Still not charging: Starboard Starter has not reached 13.1 V for 10 h 0 min (since 2026-11-18 07:36). Now 13.04 V.
Check shore power, that the charger is on, and its output to this battery (fuse, switch, wiring).

## Battery

- **13.04 V** · 100% charge · Normal · 59 °F
- Last 2 hours: lowest 13.02 V, highest 13.04 V

## Victron Orion

- **Bulk** · input 13.09 V, output 14.09 V
- Its input matches Starboard Starter (13.04 V).
- Its output matches Electronic Controls (13.81 V).
- It's running and its input matches this battery, which isn't being charged: it's drawing from it.

## Other batteries

- Port Starter: 12.60 V, 92%, Normal
- Electronic Controls: 13.81 V, 100%, Charging

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 20:59:58 | Bulk | 12.98 V |  |
| 21:00:01 | Off | 12.99 V | Engine shutdown detected |
| 00:18:06 | Off | 13.67 V |  |
| 00:18:14 | Bulk | 13.00 V |  |
| 04:16:09 | Bulk | 12.35 V |  |
| 04:16:11 | Off | 12.99 V | Engine shutdown detected |
| 07:20:29 | Off | 13.69 V |  |
| 07:20:36 | Bulk | 13.36 V |  |
| 11:18:20 | Bulk | 12.34 V |  |
| 11:18:22 | Off | 12.98 V | Engine shutdown detected |
| 14:18:40 | Off | 13.69 V |  |
| 14:18:48 | Bulk | 13.45 V |  |

## Data

- [Readings from the 2 hours before this alert](173626-starboard-starter-no-charge-repeat.csv) (CSV)
- [All readings for 2026-11-18](../../readings/2026-11-18/)

_Sent by your private Battery Monitor._
