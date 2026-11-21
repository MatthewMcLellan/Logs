# Start bank: batteries 0.76 V apart

**Sat 21 Nov 2026, 02:30:36**

Start bank is still out of balance: its two batteries are 0.76 V apart (Starboard Starter 13.27 V, Port Starter 12.51 V), more than 0.50 V since 06:20.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **25.78 V** in all · its batteries 0.76 V apart (alarm above 0.50 V)
- Starboard Starter: 13.27 V, 100%, Normal
- Port Starter: 12.51 V, 80%, Normal

## Victron Orion

- **Bulk** · input 13.11 V, output 14.27 V
- Its input matches Starboard Starter (13.27 V).
- Its output matches Electronic Controls (13.92 V).

## Other batteries

- Electronic Controls: 13.92 V, 100%, Charging

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
| 02:09:05 | Off | 13.77 V |  |
| 02:09:14 | Bulk | 13.30 V |  |

## Data

- [Readings from the 2 hours before this alert](023036-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-21](../../readings/2026-11-21/)

_Sent by your private Battery Monitor._
