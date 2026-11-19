# Start bank: batteries 0.55 V apart

**Thu 19 Nov 2026, 12:32:36**

Start bank is still out of balance: its two batteries are 0.55 V apart (Starboard Starter 13.12 V, Port Starter 12.57 V), more than 0.50 V since 06:22.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **25.69 V** in all · its batteries 0.55 V apart (alarm above 0.50 V)
- Starboard Starter: 13.12 V, 100%, Normal
- Port Starter: 12.57 V, 90%, Normal

## Victron Orion

- **Bulk** · input 13.08 V, output 14.11 V
- Its input matches Starboard Starter (13.12 V).
- Its output matches Electronic Controls (13.83 V).

## Other batteries

- Electronic Controls: 13.83 V, 100%, Charging

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
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
| 07:58:51 | Bulk | 12.35 V |  |
| 07:58:54 | Off | 12.99 V | Engine shutdown detected |
| 10:45:50 | Off | 13.68 V |  |
| 10:45:58 | Bulk | 13.15 V |  |

## Data

- [Readings from the 2 hours before this alert](123236-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-19](../../readings/2026-11-19/)

_Sent by your private Battery Monitor._
