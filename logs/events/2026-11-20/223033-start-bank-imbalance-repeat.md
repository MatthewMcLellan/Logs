# Start bank: batteries 0.73 V apart

**Fri 20 Nov 2026, 22:30:33**

Start bank is still out of balance: its two batteries are 0.73 V apart (Starboard Starter 13.25 V, Port Starter 12.52 V), more than 0.50 V since 06:20.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **25.77 V** in all · its batteries 0.73 V apart (alarm above 0.50 V)
- Starboard Starter: 13.25 V, 100%, Normal
- Port Starter: 12.52 V, 81%, Normal

## Victron Orion

- **Bulk** · input 13.10 V, output 14.11 V
- Its input matches Starboard Starter (13.25 V).
- Its output matches Electronic Controls (13.83 V).

## Other batteries

- Electronic Controls: 13.83 V, 100%, Charging

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 23:58:15 | Off | 13.67 V |  |
| 23:58:23 | Bulk | 13.00 V |  |
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

## Data

- [Readings from the 2 hours before this alert](223033-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-20](../../readings/2026-11-20/)

_Sent by your private Battery Monitor._
