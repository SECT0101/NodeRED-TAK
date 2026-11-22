# NHC Tropical Weather → TAK

Active tropical storms and hurricanes from the National Hurricane Center: current positions, forecast tracks and cones.

| | |
|---|---|
| **Data** | [NOAA NHC map services](https://mapservices.weather.noaa.gov/tropical/) |
| **Updates** | Every 15 minutes |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Click **Deploy**.

Direct link to the flow file: [nhc-tropical/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/nhc-tropical/flow.json)
