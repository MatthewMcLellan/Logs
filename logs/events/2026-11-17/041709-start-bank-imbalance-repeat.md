# Start bank: batteries 1.01 V apart

**Tue 17 Nov 2026, 04:17:09**

Start bank is still out of balance: its two batteries are 1.01 V apart (Starboard Starter 13.72 V, Port Starter 12.71 V), more than 0.50 V since 01:07.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **26.43 V** in all · its batteries 1.01 V apart (alarm above 0.50 V)
- Starboard Starter: 13.72 V, 100%, Charging
- Port Starter: 12.71 V, 100%, Normal

## Victron Orion

- **Bulk** · input 13.11 V, output 14.07 V
- Its output matches Starboard Starter (13.72 V).
- Its output matches Electronic Controls (13.81 V).

## Other batteries

- Electronic Controls: 13.81 V, 100%, Charging

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 01:06:04 | Off | 12.73 V | Engine shutdown detected |
| 02:30:46 | Off | 13.69 V |  |
| 02:30:54 | Bulk | 12.98 V |  |

## Data

- [Readings from the 2 hours before this alert](041709-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-17](../../readings/2026-11-17/)

_Sent by your private Battery Monitor._
