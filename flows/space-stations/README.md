# Space Stations → TAK

Live positions of crewed space stations (ISS, Tiangong) and related objects.

| | |
|---|---|
| **Data** | [Space-Track.org and SatNOGS DB](https://www.space-track.org/) |
| **Updates** | Every 30 seconds (orbits refreshed every 6 hours) |
| **Needs** | A free [Space-Track.org](https://www.space-track.org/auth/createAccount) account<br>The `satellite.js` module (see *Satellite and GOES flows* in the main README) |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Set **SPACETRACK_USER** and **SPACETRACK_PASS** in the tab's Environment Variables (keep the password type as *credential*).
4. Click **Deploy**.

Direct link to the flow file: [space-stations/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/space-stations/flow.json)
