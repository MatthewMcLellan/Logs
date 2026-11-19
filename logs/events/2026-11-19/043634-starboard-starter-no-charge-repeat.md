# Starboard Starter: not charging for 21 h 0 min

**Thu 19 Nov 2026, 04:36:34**

Still not charging: Starboard Starter has not reached 13.1 V for 21 h 0 min (since 2026-11-18 07:36). Now 13.08 V.
Check shore power, that the charger is on, and its output to this battery (fuse, switch, wiring).

## Battery

- **13.08 V** · 100% charge · Normal · 57 °F
- Last 2 hours: lowest 13.07 V, highest 13.09 V

## Victron Orion

- **Bulk** · input 13.09 V, output 14.13 V
- Its input matches Starboard Starter (13.08 V).
- Its output matches Electronic Controls (13.82 V).
- It's running and its input matches this battery, which isn't being charged: it's drawing from it.

## Other batteries

- Port Starter: 12.58 V, 90%, Normal
- Electronic Controls: 13.82 V, 100%, Charging

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 07:20:29 | Off | 13.69 V |  |
| 07:20:36 | Bulk | 13.36 V |  |
| 11:18:20 | Bulk | 12.34 V |  |
| 11:18:22 | Off | 12.98 V | Engine shutdown detected |
| 14:18:40 | Off | 13.69 V |  |
| 14:18:48 | Bulk | 13.45 V |  |
| 18:16:30 | Bulk | 12.34 V |  |
| 18:16:32 | Off | 12.98 V | Engine shutdown detected |
| 21:09:40 | Off | 13.65 V |  |
| 21:09:48 | Bulk | 12.97 V |  |
| 01:07:41 | Bulk | 12.98 V |  |
| 01:07:43 | Off | 12.99 V | Engine shutdown detected |
| 04:01:10 | Off | 13.67 V |  |
| 04:01:18 | Bulk | 13.13 V |  |

## Data

- [Readings from the 2 hours before this alert](043634-starboard-starter-no-charge-repeat.csv) (CSV)
- [All readings for 2026-11-19](../../readings/2026-11-19/)

_Sent by your private Battery Monitor._
