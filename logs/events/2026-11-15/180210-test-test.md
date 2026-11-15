# Test alert: Boat battery

**Sun 15 Nov 2026, 18:02:10**

Test alert from Battery Monitor for Boat battery at 2026-11-15 18:02.
If you received this, alerts work.

## Battery

- **12.27 V** · 50% charge · Abnormal · 68 °F
- Last 2 hours: lowest 12.27 V, highest 12.29 V

## Victron Orion

- **Power supply** · input 13.68 V, output 13.66 V
- It's running while this battery isn't being charged: if its input is this battery, it's draining it.

Orion state changes, last 24 hours:

| Time | State | Input | Why off |
|---|---|---|---|
| 17:50:46 | Off | 13.66 V | Engine shutdown detected |
| 17:58:15 | Off | 13.68 V |  |
| 17:58:25 | Bulk | 13.48 V |  |
| 17:59:25 | Absorption | 13.47 V |  |
| 17:59:59 | Bulk |  |  |
| 18:00:00 | Off |  |  |
| 18:00:03 | Bulk | 13.69 V |  |
| 18:00:10 | Off | 13.47 V |  |
| 18:00:13 | Bulk | 13.62 V |  |
| 18:00:49 | Power supply | 13.48 V |  |

## Data

- [Readings from the 2 hours before this alert](180210-test-test.csv) (CSV)
- [All readings for 2026-11-15](../../readings/2026-11-15/)

_Sent by your private Battery Monitor._
