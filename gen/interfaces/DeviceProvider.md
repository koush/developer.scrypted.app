[Scrypted Documentation](../globals.md) / DeviceProvider

# Interface: DeviceProvider

DeviceProvider acts as a controller/hub and exposes multiple devices to Scrypted Device Manager.

## Methods

### getDevice()

> **getDevice**(`nativeId`): `Promise`\<`any`\>

Get an instance of a previously discovered device that was reported to the device manager.
This method will be called every time onDeviceDiscovered or onDevicesChanged is invoked
by the plugin. A previously returned instance may be returned again. If a different
instance is returned, the plugin is responsible for cleaning up the old instance.

#### Parameters

• **nativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Promise`\<`any`\>

***

### releaseDevice()

> **releaseDevice**(`id`, `nativeId`): `Promise`\<`void`\>

Called when a previously returned device from getDevice was deleted from Scrypted.

#### Parameters

• **id**: `string`

• **nativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Promise`\<`void`\>
