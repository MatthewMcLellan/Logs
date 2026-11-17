# Start bank: batteries 0.51 V apart

**Tue 17 Nov 2026, 02:17:07**

Start bank is still out of balance: its two batteries are 0.51 V apart (Starboard Starter 13.23 V, Port Starter 12.72 V), more than 0.50 V since 01:07.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **25.95 V** in all · its batteries 0.51 V apart (alarm above 0.50 V)
- Starboard Starter: 13.23 V, 100%, Normal
- Port Starter: 12.72 V, 100%, Normal

## Victron Orion

- **Off** (Engine shutdown detected) · input 12.67 V
- Its input matches Port Starter (12.72 V).
- Its input matches Electronic Controls (12.66 V).

## Other batteries

- Electronic Controls: 12.66 V, 96%, Normal

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 01:06:04 | Off | 12.73 V | Engine shutdown detected |

## Data

- [Readings from the 2 hours before this alert](021707-start-bank-imbalance-repeat.csv) (CSV)
- [All readings for 2026-11-17](../../readings/2026-11-17/)

_Sent by your private Battery Monitor._
