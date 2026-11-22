# CalTopo → TAK

Streams a CalTopo map into TAK: markers with matching TAK icons, lines and shapes, and live-tracked team members. Items deleted in CalTopo are deleted in TAK.

| | |
|---|---|
| **Data** | [CalTopo](https://caltopo.com/) |
| **Updates** | Every 60 seconds |
| **Needs** | A CalTopo map shared so that anyone with the link can view it |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Put your map ID (the code after `caltopo.com/m/`) in the **Fetch JSON** node's URL, replacing `YOUR_MAP_ID`.
4. Rename the **CalTopo Engine** function to `CalTopo Engine - <your map name>`. That name becomes the map label in TAK.
5. Optional: list team members to show as live positions in `LIVE_TRACK_NAMES` at the top of the engine.
6. For more maps, copy the inject, Fetch JSON and engine nodes and give each its own map ID and name.
7. The icon paths are for standard TAK iconsets. Markers whose icon isn't installed on your server show as a plain dot.
8. Click **Deploy**.

Direct link to the flow file: [caltopo-streamer/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/caltopo-streamer/flow.json)
