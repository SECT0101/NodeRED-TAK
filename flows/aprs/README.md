# APRS Stations → TAK

Live APRS stations in Tennessee (plus a small buffer): mobiles, digipeaters, iGates, objects and weather stations (wind and temperature in the remarks, in °F). Stations show as friendly.

| | |
|---|---|
| **Data** | [APRS-IS (aprs2.net)](https://www.aprs2.net/) |
| **Updates** | Live (as stations beacon) |
| **Needs** | [node-red-contrib-tcp-client](https://flows.nodered.org/node/node-red-contrib-tcp-client) (Manage palette > Install) |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Set **APRS_CALLSIGN** in the tab's Environment Variables to your callsign. The flow logs in receive-only (passcode -1), so no passcode is needed.
4. Click **Deploy**.

Direct link to the flow file: [aprs/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/aprs/flow.json)
