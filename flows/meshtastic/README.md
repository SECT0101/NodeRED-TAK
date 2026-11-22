# Meshtastic Nodes → TAK

Meshtastic radios in Tennessee (plus a small buffer) that publish their position to the public Meshtastic MQTT server, shown with their node names. Only nodes whose owners turned on MQTT uplink or map reports appear, and only the default public LongFast channel is decoded.

| | |
|---|---|
| **Data** | [Meshtastic public MQTT server](https://meshtastic.org/docs/software/integrations/mqtt/) |
| **Updates** | Live (as nodes report; markers stay 60 minutes) |
| **Needs** | [node-red-contrib-meshtastic-advanced](https://flows.nodered.org/node/node-red-contrib-meshtastic-advanced) (Manage palette > Install) |

## Setup

1. Import `flow.json` (see [Importing a flow](../../README.md#importing-a-flow)).
2. Double-click **TAK Server :8089**, set your TAK Server address, then edit its TLS config and upload your client certificate and key.
3. Edit the **Meshtastic public MQTT** broker, open **Security**, and enter the public login `meshdev` / `large4cats` (the published login for mqtt.meshtastic.org).
4. Click **Deploy**.

Direct link to the flow file: [meshtastic/flow.json](https://raw.githubusercontent.com/SECT0101/NodeRED-TAK/main/flows/meshtastic/flow.json)
