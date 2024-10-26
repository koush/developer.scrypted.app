[Scrypted Documentation](../globals.md) / DeviceDiscovery

# Interface: DeviceDiscovery

A DeviceProvider that has a device discovery mechanism.

## Methods

### discoverDevices()

> **discoverDevices**(`scan`?): `Promise`\<[`DiscoveredDevice`](DiscoveredDevice.md)[]\>

Perform device discovery, scanning if requested.
If no scan is requested, the current list of discovered devices
is returned.

#### Parameters

• **scan?**: `boolean`

#### Returns

`Promise`\<[`DiscoveredDevice`](DiscoveredDevice.md)[]\>

***

### adoptDevice()

> **adoptDevice**(`device`): `Promise`\<`string`\>

Returns the id of the newly adopted device.

#### Parameters

• **device**: [`AdoptDevice`](AdoptDevice.md)

#### Returns

`Promise`\<`string`\>
