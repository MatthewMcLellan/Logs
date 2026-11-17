# Start bank: batteries 1.23 V apart

**Tue 17 Nov 2026, 01:17:07**

Start bank is out of balance: its two batteries are 1.23 V apart (Starboard Starter 13.95 V, Port Starter 12.72 V), more than 0.50 V since 01:07.
In a series bank both should read about the same. One is getting more charge than the other (a charger on one battery only), or one is weaker. Check that the bank's charger is connected across the whole bank.

## Bank

- **26.67 V** in all · its batteries 1.23 V apart (alarm above 0.50 V)
- Starboard Starter: 13.95 V, 100%, Charging
- Port Starter: 12.72 V, 100%, Normal

## Victron Orion

- **Off** (Engine shutdown detected) · input 12.75 V
- Its input matches Port Starter (12.72 V).
- Its input matches Electronic Controls (12.72 V).

## Other batteries

- Electronic Controls: 12.72 V, 100%, Normal

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 01:06:04 | Off | 12.73 V | Engine shutdown detected |

## Data

- [Readings from the 2 hours before this alert](011707-start-bank-imbalance-start.csv) (CSV)
- [All readings for 2026-11-17](../../readings/2026-11-17/)

_Sent by your private Battery Monitor._
