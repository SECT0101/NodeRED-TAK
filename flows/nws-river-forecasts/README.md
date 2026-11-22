# NWS River Forecasts → TAK

NWS forecast river gauges, colored by the worst observed or forecast flood level (purple major, red moderate, orange minor, yellow action, green none). The forecast crest is in the marker remarks.

| | |
|---|---|
| **Data** | [NWS National Water Prediction Service](https://water.noaa.gov/) |
| **Updates** | Every 15 minutes |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Click **Deploy**.

Direct link to the flow file: [nws-river-forecasts/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/nws-river-forecasts/flow.json)
