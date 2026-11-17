# Start bank: batteries 0.56 V apart

**Tue 17 Nov 2026, 14:57:12**

Start bank is still out of balance: its two batteries are 0.56 V apart (Starboard Starter 13.22 V, Port Starter 12.66 V), more than 0.50 V since 13:47.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **25.88 V** in all · its batteries 0.56 V apart (alarm above 0.50 V)
- Starboard Starter: 13.22 V, 100%, Normal
- Port Starter: 12.66 V, 96%, Normal

## Victron Orion

- **Off** (Engine shutdown detected) · input 12.82 V
- Its input matches Port Starter (12.66 V).
- Its input matches Electronic Controls (12.80 V).

## Other batteries

- Electronic Controls: 12.80 V, 100%, Normal

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

## Data

- [Readings from the 2 hours before this alert](145712-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-17](../../readings/2026-11-17/)

_Sent by your private Battery Monitor._
