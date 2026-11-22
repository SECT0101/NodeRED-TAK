# NWS Local Storm Reports → TAK

Storm reports from spotters, emergency managers and the public (tornadoes, wind damage, hail, flooding) for Tennessee, last 24 hours.

| | |
|---|---|
| **Data** | [Iowa Environmental Mesonet LSR feed](https://mesonet.agron.iastate.edu/request/gis/lsrs.phtml) |
| **Updates** | Every 5 minutes |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Click **Deploy**.

Direct link to the flow file: [nws-storm-reports/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/nws-storm-reports/flow.json)
