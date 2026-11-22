# GOES Lightning (GLM) → TAK

Lightning flashes over Tennessee (plus a small buffer) from the GOES-East Geostationary Lightning Mapper, colored by age (yellow under 5 min, orange 5-10, red 10-15) with flash energy and size in the remarks. Markers drop off after 15 minutes.

| | |
|---|---|
| **Data** | [NOAA GOES-R GLM on AWS Open Data](https://registry.opendata.aws/noaa-goes/) |
| **Updates** | Every 60 seconds (new satellite files every 20 seconds) |
| **Needs** | The `jsfive` module (see *Satellite and GOES flows* in the main README: same `functionExternalModules: true` setting) |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Optional: set **TAK_CHANNEL** in the tab's Environment Variables to send the markers to a TAK channel (for example `NWS`).
4. Optional: set **GOES_BUCKET** to `noaa-goes18` for GOES-West (default `noaa-goes19`, GOES-East).
5. Click **Deploy**.

**Note:** GLM sees total lightning (in-cloud and cloud-to-ground) from orbit, at about 8 km resolution. Treat it as storm awareness, not as an exact strike location.

Direct link to the flow file: [goes-glm-lightning/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/goes-glm-lightning/flow.json)
