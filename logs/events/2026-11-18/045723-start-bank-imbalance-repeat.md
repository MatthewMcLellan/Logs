# Start bank: batteries 1.65 V apart

**Wed 18 Nov 2026, 04:57:23**

Start bank is still out of balance: its two batteries are 1.65 V apart (Starboard Starter 14.28 V, Port Starter 12.63 V), more than 0.50 V since 13:47.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **26.91 V** in all · its batteries 1.65 V apart (alarm above 0.50 V)
- Starboard Starter: 14.28 V, 100%, Charging
- Port Starter: 12.63 V, 94%, Normal

## Victron Orion

- **Off** (Engine shutdown detected) · input 12.88 V
- Its input matches Port Starter (12.63 V).
- Its input matches Electronic Controls (12.86 V).

## Other batteries

- Electronic Controls: 12.86 V, 100%, Normal

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 06:28:35 | Bulk | 12.33 V |  |
| 06:28:38 | Off | 12.98 V | Engine shutdown detected |
| 09:42:06 | Off | 13.68 V |  |
| 09:42:14 | Bulk | 13.01 V |  |
| 13:39:45 | Bulk | 12.33 V |  |
| 13:39:47 | Off | 12.98 V | Engine shutdown detected |
| 17:02:57 | Off | 13.68 V |  |
| 17:03:01 | Bulk | 13.67 V |  |
| 20:59:58 | Bulk | 12.98 V |  |
| 21:00:01 | Off | 12.99 V | Engine shutdown detected |
| 00:18:06 | Off | 13.67 V |  |
| 00:18:14 | Bulk | 13.00 V |  |
| 04:16:09 | Bulk | 12.35 V |  |
| 04:16:11 | Off | 12.99 V | Engine shutdown detected |

## Data

- [Readings from the 2 hours before this alert](045723-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-18](../../readings/2026-11-18/)

_Sent by your private Battery Monitor._
