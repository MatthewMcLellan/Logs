# Start bank: batteries 0.95 V apart

**Tue 17 Nov 2026, 20:57:17**

Start bank is still out of balance: its two batteries are 0.95 V apart (Starboard Starter 13.59 V, Port Starter 12.64 V), more than 0.50 V since 13:47.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **26.23 V** in all · its batteries 0.95 V apart (alarm above 0.50 V)
- Starboard Starter: 13.59 V, 100%, Charging
- Port Starter: 12.64 V, 95%, Normal

## Victron Orion

- **Bulk** · input 13.09 V, output 14.08 V
- Its output matches Electronic Controls (13.81 V).

## Other batteries

- Electronic Controls: 13.81 V, 100%, Charging

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 01:06:04 | Off | 12.73 V | Engine shutdown detected |
| 02:30:46 | Off | 13.69 V |  |
| 02:30:54 | Bulk | 12.98 V |  |
| 06:28:35 | Bulk | 12.33 V |  |
| 06:28:38 | Off | 12.98 V | Engine shutdown detected |
| 09:42:06 | Off | 13.68 V |  |
| 09:42:14 | Bulk | 13.01 V |  |
| 13:39:45 | Bulk | 12.33 V |  |
| 13:39:47 | Off | 12.98 V | Engine shutdown detected |
| 17:02:57 | Off | 13.68 V |  |
| 17:03:01 | Bulk | 13.67 V |  |

## Data

- [Readings from the 2 hours before this alert](205717-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-17](../../readings/2026-11-17/)

_Sent by your private Battery Monitor._
