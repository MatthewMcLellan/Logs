# Start bank: batteries 0.63 V apart

**Fri 20 Nov 2026, 04:32:47**

Start bank is still out of balance: its two batteries are 0.63 V apart (Starboard Starter 13.18 V, Port Starter 12.55 V), more than 0.50 V since 06:22.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **25.73 V** in all · its batteries 0.63 V apart (alarm above 0.50 V)
- Starboard Starter: 13.18 V, 100%, Normal
- Port Starter: 12.55 V, 86%, Normal

## Victron Orion

- **Off** (Engine shutdown detected) · input 12.88 V
- Its input matches Starboard Starter (13.18 V).
- Its input matches Port Starter (12.55 V).
- Its input matches Electronic Controls (12.86 V).

## Other batteries

- Electronic Controls: 12.86 V, 100%, Normal

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 07:58:51 | Bulk | 12.35 V |  |
| 07:58:54 | Off | 12.99 V | Engine shutdown detected |
| 10:45:50 | Off | 13.68 V |  |
| 10:45:58 | Bulk | 13.15 V |  |
| 14:44:02 | Bulk | 12.97 V |  |
| 14:44:04 | Off | 12.98 V | Engine shutdown detected |
| 17:19:27 | Off | 13.71 V |  |
| 17:19:35 | Bulk | 13.15 V |  |
| 21:17:12 | Bulk | 12.81 V |  |
| 21:17:14 | Off | 12.97 V | Engine shutdown detected |
| 23:58:15 | Off | 13.67 V |  |
| 23:58:23 | Bulk | 13.00 V |  |
| 03:55:21 | Bulk | 12.98 V |  |
| 03:55:24 | Off | 12.99 V | Engine shutdown detected |

## Data

- [Readings from the 2 hours before this alert](043247-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-20](../../readings/2026-11-20/)

_Sent by your private Battery Monitor._
