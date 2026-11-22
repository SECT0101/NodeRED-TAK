# FEMA Disaster Declarations → TAK

Tennessee counties under an ongoing FEMA declaration from the last 365 days, drawn as county outlines: major disaster red, emergency orange, fire management yellow.

| | |
|---|---|
| **Data** | [OpenFEMA and Census TIGERweb](https://www.fema.gov/about/openfema/data-sets) |
| **Updates** | Every 6 hours |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Click **Deploy**.

Direct link to the flow file: [fema-disaster-declarations/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/fema-disaster-declarations/flow.json)
