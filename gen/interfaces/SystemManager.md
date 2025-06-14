[Scrypted Documentation](../globals.md) / SystemManager

# Interface: SystemManager

SystemManager is used by scripts to query device state and access devices.

## Methods

### getComponent()

> **getComponent**(`id`): `Promise`\<`any`\>

Retrieve a system service.

#### Parameters

• **id**: `string`

#### Returns

`Promise`\<`any`\>

***

### getDeviceById()

#### getDeviceById(id)

> **getDeviceById**(`id`): [`ScryptedDevice`](ScryptedDevice.md)

Find a Scrypted device by id.

##### Parameters

• **id**: `string`

##### Returns

[`ScryptedDevice`](ScryptedDevice.md)

#### getDeviceById(id)

> **getDeviceById**\<`T`\>(`id`): [`ScryptedDevice`](ScryptedDevice.md) & `T`

Find a Scrypted device by id.

##### Type Parameters

• **T**

##### Parameters

• **id**: `string`

##### Returns

[`ScryptedDevice`](ScryptedDevice.md) & `T`

#### getDeviceById(pluginId, nativeId)

> **getDeviceById**(`pluginId`, `nativeId`?): [`ScryptedDevice`](ScryptedDevice.md)

Find a Scrypted device by pluginId and optionally the nativeId.

##### Parameters

• **pluginId**: `string`

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

##### Returns

[`ScryptedDevice`](ScryptedDevice.md)

#### getDeviceById(pluginId, nativeId)

> **getDeviceById**\<`T`\>(`pluginId`, `nativeId`?): [`ScryptedDevice`](ScryptedDevice.md) & `T`

Find a Scrypted device by pluginId and optionally the nativeId.

##### Type Parameters

• **T**

##### Parameters

• **pluginId**: `string`

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

##### Returns

[`ScryptedDevice`](ScryptedDevice.md) & `T`

***

### getDeviceByName()

#### getDeviceByName(name)

> **getDeviceByName**(`name`): [`ScryptedDevice`](ScryptedDevice.md)

Find a Scrypted device by name.

##### Parameters

• **name**: `string`

##### Returns

[`ScryptedDevice`](ScryptedDevice.md)

#### getDeviceByName(name)

> **getDeviceByName**\<`T`\>(`name`): [`ScryptedDevice`](ScryptedDevice.md) & `T`

Find a Scrypted device by name.

##### Type Parameters

• **T**

##### Parameters

• **name**: `string`

##### Returns

[`ScryptedDevice`](ScryptedDevice.md) & `T`

***

### getSystemState()

> **getSystemState**(): `object`

Get the current state of every device.

#### Returns

`object`

***

### listen()

> **listen**(`callback`): [`EventListenerRegister`](EventListenerRegister.md)

Passively (without polling) listen to property changed events.

#### Parameters

• **callback**: [`EventListener`](../type-aliases/EventListener.md)

#### Returns

[`EventListenerRegister`](EventListenerRegister.md)

***

### listenDevice()

> **listenDevice**(`id`, `event`, `callback`): [`EventListenerRegister`](EventListenerRegister.md)

Subscribe to events from a specific interface on a device id, such as 'OnOff' or 'Brightness'. This is a convenience method for ScryptedDevice.listen.

#### Parameters

• **id**: `string`

• **event**: `string` \| [`EventListenerOptions`](EventListenerOptions.md)

• **callback**: [`EventListener`](../type-aliases/EventListener.md)

#### Returns

[`EventListenerRegister`](EventListenerRegister.md)

***

### removeDevice()

> **removeDevice**(`id`): `Promise`\<`void`\>

Remove a device from Scrypted. Plugins should use DeviceManager.onDevicesChanged or DeviceManager.onDeviceRemoved to remove their own devices

#### Parameters

• **id**: `string`

#### Returns

`Promise`\<`void`\>
