# Space Weather → TAK

One status marker colored by the current geomagnetic storm level (NOAA G-scale from the Kp index), with active space weather alerts in the remarks. Handy for judging HF conditions.

| | |
|---|---|
| **Data** | [NOAA Space Weather Prediction Center](https://www.swpc.noaa.gov/) |
| **Updates** | Every 5 minutes |
| **Needs** | Nothing extra, only core Node-RED nodes |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. The marker's position is set at the top of the **Build status CoT** function.
4. Click **Deploy**.

Direct link to the flow file: [space-weather/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/space-weather/flow.json)
