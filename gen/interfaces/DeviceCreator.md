[Scrypted Documentation](../globals.md) / DeviceCreator

# Interface: DeviceCreator

A DeviceProvider that allows the user to create a device.

## Methods

### getCreateDeviceSettings()

> **getCreateDeviceSettings**(): `Promise`\<[`Setting`](Setting.md)[]\>

#### Returns

`Promise`\<[`Setting`](Setting.md)[]\>

***

### createDevice()

> **createDevice**(`settings`): `Promise`\<`string`\>

Return the id of the created device.

#### Parameters

• **settings**: [`DeviceCreatorSettings`](DeviceCreatorSettings.md)

#### Returns

`Promise`\<`string`\>
