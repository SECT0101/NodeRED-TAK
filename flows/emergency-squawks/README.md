# Emergency & Wildfire Squawks → TAK

Aircraft squawking 7500 (hijack), 7600 (lost comms), 7700 (emergency) or 1255 (firefighting) over Tennessee (plus a small buffer).

| | |
|---|---|
| **Data** | [adsb.fi open data API](https://github.com/adsbfi/opendata) |
| **Updates** | Every 17 seconds |
| **Needs** | [node-red-contrib-tak](https://flows.nodered.org/node/node-red-contrib-tak) (Manage palette > Install) |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Click **Deploy**.

Direct link to the flow file: [emergency-squawks/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/emergency-squawks/flow.json)
