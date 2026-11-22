# FEMA Open Shelters → TAK

Open shelters in Tennessee from the FEMA National Shelter System (Red Cross and partners). Closed shelters are left off.

| | |
|---|---|
| **Data** | [FEMA National Shelter System](https://gis.fema.gov/) |
| **Updates** | Every 15 minutes |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Click **Deploy**.

Direct link to the flow file: [fema-open-shelters/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/fema-open-shelters/flow.json)
