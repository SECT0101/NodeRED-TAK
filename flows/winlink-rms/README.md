# Winlink RMS Gateways → TAK

Public Winlink RMS gateways, HF (PACTOR) and VHF/UHF (packet), with callsign, grid square and frequencies.

| | |
|---|---|
| **Data** | [Winlink CMS public listings](https://winlink.org/RMSChannels) |
| **Updates** | Every 15 minutes |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Click **Deploy**.

Direct link to the flow file: [winlink-rms/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/winlink-rms/flow.json)
