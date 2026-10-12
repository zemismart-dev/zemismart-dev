# Zemismart

### Smart home products and integrations

[Official website](https://www.zemismart.com/) · [Community](https://forum.zemismart.com/) · [GitHub repositories](https://github.com/zemismart-dev?tab=repositories)

Zemismart develops smart home products including motorized curtains and blinds, wall switches, lighting, sensors, and gateways. Our range includes products using Matter, Thread, Zigbee, and Wi-Fi. Supported platforms and features depend on the specific model and firmware.

This is the Zemismart development account. We share device integrations, configuration files, and setup guides, and contribute device support to open-source smart home projects.

## Device integrations

| Project | What you will find |
| --- | --- |
| [Zigbee2MQTT converters](https://github.com/zemismart-dev/zigbee2mqtt) | External converters, device fingerprints, feature descriptions, and installation guides. |
| [ZHA quirks](https://github.com/zemismart-dev/zemismart-zha-quirks) | Custom device handlers for Home Assistant's ZHA integration. |
| [Screen Switch Name Hook](https://github.com/zemismart-dev/screen-switch-name-hook) | Synchronize Home Assistant entity names to supported Zemismart screen switches. |
| [AD35 HA Panel](https://github.com/zemismart-dev/ad35-ha-panel) | Connect the AD35-S3 panel to Home Assistant and configure its display and firmware updates. |

Start with the README in the relevant repository and check the exact device model and fingerprint before installing a converter or quirk. English is the primary documentation language; Chinese guides are available in individual repositories.

## Open-source collaboration

Our forks support development and contributions to these upstream projects:

- [zigpy/zha-device-handlers](https://github.com/zigpy/zha-device-handlers)
- [Koenkk/zigbee-herdsman-converters](https://github.com/Koenkk/zigbee-herdsman-converters)
- [Koenkk/zigbee2mqtt.io](https://github.com/Koenkk/zigbee2mqtt.io)
- [SmartThingsCommunity/SmartThingsEdgeDrivers](https://github.com/SmartThingsCommunity/SmartThingsEdgeDrivers)

Each project retains its own maintainers, license, and contribution guidelines. Work in a Zemismart fork does not by itself mean that a change has been accepted upstream.

## Get in touch

- **Products and customer service:** visit [zemismart.com](https://www.zemismart.com/).
- **Community discussion:** join the [Zemismart community](https://forum.zemismart.com/).
- **Integration issues:** open an issue in the relevant repository with the device model, firmware and platform versions, and a description of the problem. Remove credentials and personal information from logs before sharing them.
