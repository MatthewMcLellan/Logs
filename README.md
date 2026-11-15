# Battery logs

Written by the private Battery Monitor dashboard:

- `readings/<date>/<HHMM>.csv`: every reading, in 10-minute files
- `stored/`: downloads of the monitor's own stored log, with the drain and charging check
- `events/<date>/`: a report for each alert, with the readings from the 2 hours before it

This branch holds only logs; the code is on the main branch.
