# Start bank: batteries 0.56 V apart

**Thu 19 Nov 2026, 18:32:40**

Start bank is still out of balance: its two batteries are 0.56 V apart (Starboard Starter 13.13 V, Port Starter 12.57 V), more than 0.50 V since 06:22.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **25.70 V** in all · its batteries 0.56 V apart (alarm above 0.50 V)
- Starboard Starter: 13.13 V, 100%, Normal
- Port Starter: 12.57 V, 88%, Normal

## Victron Orion

- **Bulk** · input 13.09 V, output 14.18 V
- Its input matches Starboard Starter (13.13 V).
- Its output matches Electronic Controls (13.87 V).

## Other batteries

- Electronic Controls: 13.87 V, 100%, Charging

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 21:09:40 | Off | 13.65 V |  |
| 21:09:48 | Bulk | 12.97 V |  |
| 01:07:41 | Bulk | 12.98 V |  |
| 01:07:43 | Off | 12.99 V | Engine shutdown detected |
| 04:01:10 | Off | 13.67 V |  |
| 04:01:18 | Bulk | 13.13 V |  |
| 07:58:51 | Bulk | 12.35 V |  |
| 07:58:54 | Off | 12.99 V | Engine shutdown detected |
| 10:45:50 | Off | 13.68 V |  |
| 10:45:58 | Bulk | 13.15 V |  |
| 14:44:02 | Bulk | 12.97 V |  |
| 14:44:04 | Off | 12.98 V | Engine shutdown detected |
| 17:19:27 | Off | 13.71 V |  |
| 17:19:35 | Bulk | 13.15 V |  |

## Data

- [Readings from the 2 hours before this alert](183240-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-19](../../readings/2026-11-19/)

_Sent by your private Battery Monitor._
