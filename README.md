# RF-condition

4G + 5G RSRP / RSRQ Mobility Dashboard.

## Publish
The dashboard is deployed automatically to GitHub Pages when changes are pushed to `main`.

## Features
- Separate Excel/CSV uploads for 4G EUTRAN/LTE and 5G NR NSA
- RSRP and RSRQ trend charts
- Date, time, NE, cell, technology, and metric filters
- Bad-signal map for records with valid GPS coordinates
- Degraded-record table and CSV export

## Radio thresholds
- Bad RSRP: below -105 dBm
- Bad RSRQ: below -16 dB

Uploaded measurement files are processed locally in the browser and are not sent to a server.
