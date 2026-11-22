# USGS Water → TAK

River and stream gauges: gauge height and flow at every active USGS site in Tennessee (plus a small buffer).

| | |
|---|---|
| **Data** | [USGS Water Services](https://waterservices.usgs.gov/) |
| **Updates** | Every 15 minutes |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Set a contact email in the **User-Agent** header of the USGS request node (USGS asks for one).
4. Click **Deploy**.

Direct link to the flow file: [usgs-water/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/usgs-water/flow.json)
