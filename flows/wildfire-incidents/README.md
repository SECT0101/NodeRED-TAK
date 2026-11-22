# Wildfire Incidents & Perimeters → TAK

Current wildfire incidents and their mapped fire perimeters. Fires that leave the feed are removed from the map.

| | |
|---|---|
| **Data** | [Esri USA Wildfires (NIFC data)](https://www.arcgis.com/home/item.html?id=d957997ccee7408287a963600a77f61f) |
| **Updates** | Every 15 minutes |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Click **Deploy**.

Direct link to the flow file: [wildfire-incidents/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/wildfire-incidents/flow.json)
