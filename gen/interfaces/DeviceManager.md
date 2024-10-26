[Scrypted Documentation](../globals.md) / DeviceManager

# Interface: DeviceManager

DeviceManager is the interface used by DeviceProvider to report new devices, device states, and device events to Scrypted.

## Methods

### getDeviceLogger()

> **getDeviceLogger**(`nativeId`?): [`Logger`](Logger.md)

Get the logger for a device given a native id.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

[`Logger`](Logger.md)

***

### getDeviceConsole()

> **getDeviceConsole**(`nativeId`?): `Console`

Get the console for the device given a native id.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Console`

***

### getMixinConsole()

> **getMixinConsole**(`mixinId`, `nativeId`?): `Console`

Get the console for the device given a native id.

#### Parameters

• **mixinId**: `string`

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Console`

***

### getDeviceState()

> **getDeviceState**(`nativeId`?): [`DeviceState`](DeviceState.md)

Get the device state maintained by Scrypted. Setting properties on this state will update the state in Scrypted.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

[`DeviceState`](DeviceState.md)

***

### createDeviceState()

> **createDeviceState**(`id`, `setState`): [`WritableDeviceState`](WritableDeviceState.md)

Create a device state object that will trap all state setting calls. Used internally by mixins and fork.

#### Parameters

• **id**: `string`

• **setState**

#### Returns

[`WritableDeviceState`](WritableDeviceState.md)

***

### getMixinStorage()

> **getMixinStorage**(`id`, `nativeId`?): `Storage`

Get the storage for a mixin.

#### Parameters

• **id**: `string`

The id of the device being mixined.

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

The nativeId of the MixinProvider.

#### Returns

`Storage`

***

### onMixinEvent()

> **onMixinEvent**(`id`, `mixinDevice`, `eventInterface`, `eventData`): `Promise`\<`void`\>

Fire an event for a mixin provided by this plugin.

#### Parameters

• **id**: `string`

• **mixinDevice**: `any`

• **eventInterface**: `string`

• **eventData**: `any`

#### Returns

`Promise`\<`void`\>

***

### getDeviceStorage()

> **getDeviceStorage**(`nativeId`?): `Storage`

Get the device Storage object.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Storage`

***

### getNativeIds()

> **getNativeIds**(): `string`[]

Get all the native ids that have been reported by this plugin. This always includes "undefined", the plugin itself.

#### Returns

`string`[]

***

### onDeviceDiscovered()

> **onDeviceDiscovered**(`device`): `Promise`\<`string`\>

onDeviceDiscovered is used to report new devices that are trickle discovered, one by one, such as via a network broadcast.

#### Parameters

• **device**: [`Device`](Device.md)

#### Returns

`Promise`\<`string`\>

***

### onDeviceEvent()

> **onDeviceEvent**(`nativeId`, `eventInterface`, `eventData`): `Promise`\<`void`\>

Fire an event for a device provided by this plugin.

#### Parameters

• **nativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

• **eventInterface**: `string`

• **eventData**: `any`

#### Returns

`Promise`\<`void`\>

***

### onDeviceRemoved()

> **onDeviceRemoved**(`nativeId`): `Promise`\<`void`\>

onDeviceRemoved is used to report when discovered devices are removed.

#### Parameters

• **nativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Promise`\<`void`\>

***

### onDevicesChanged()

> **onDevicesChanged**(`devices`): `Promise`\<`void`\>

onDevicesChanged is used to sync Scrypted with devices that are attached to a hub, such as Hue or SmartThings. All the devices should be reported at once.

#### Parameters

• **devices**: [`DeviceManifest`](DeviceManifest.md)

#### Returns

`Promise`\<`void`\>

***

### requestRestart()

> **requestRestart**(): `Promise`\<`void`\>

Restart the plugin. May not happen immediately.

#### Returns

`Promise`\<`void`\>
