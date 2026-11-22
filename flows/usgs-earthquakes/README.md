# USGS Earthquakes → TAK

Earthquakes of any magnitude from the past hour, inside Tennessee (plus a small buffer).

| | |
|---|---|
| **Data** | [USGS earthquake GeoJSON feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) |
| **Updates** | Every 60 seconds |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Channel name and CoT type are at the top of the **Build CoT (TN bbox)** function.
4. Click **Deploy**.

Direct link to the flow file: [usgs-earthquakes/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/usgs-earthquakes/flow.json)
