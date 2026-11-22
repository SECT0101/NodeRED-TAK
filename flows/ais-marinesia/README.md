# Marinesia AIS Vessels → TAK

Boats and ships on Tennessee rivers and lakes from AIS, with MIL-STD-2525 vessel symbols by type (tug, towing, pleasure craft, fishing, passenger and more), flag, destination and navigation status.

| | |
|---|---|
| **Data** | [Marinesia AIS API](https://marinesia.com/) |
| **Updates** | Every 30 seconds |
| **Needs** | Your own [Marinesia](https://marinesia.com/) API key (a free trial key allows 5 requests a minute) |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Set **MARINESIA_API_KEY** in the tab's Environment Variables (keep the type as *credential*). Don't share your key.
4. Click **Deploy**.

**Note:** Marinesia's terms don't allow reselling or redistributing their data. Check them before sharing the feed outside your own team: https://marinesia.com/terms

Direct link to the flow file: [ais-marinesia/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/ais-marinesia/flow.json)
