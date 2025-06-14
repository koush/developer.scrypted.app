[Scrypted Documentation](../globals.md) / ScryptedDevice

# Interface: ScryptedDevice

All devices in Scrypted implement ScryptedDevice, which contains the id, name, and type. Add listeners to subscribe to events from that device.

## Properties

### id

> **id**: `string`

***

### nativeId?

> `optional` **nativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

***

### pluginId

> **pluginId**: `string`

***

### interfaces

> **interfaces**: `string`[]

***

### mixins

> **mixins**: `string`[]

***

### name?

> `optional` **name**: `string`

***

### info?

> `optional` **info**: [`DeviceInformation`](DeviceInformation.md)

***

### providedInterfaces

> **providedInterfaces**: `string`[]

***

### providedName?

> `optional` **providedName**: `string`

***

### providedRoom?

> `optional` **providedRoom**: `string`

***

### providedType?

> `optional` **providedType**: `string`

***

### providerId?

> `optional` **providerId**: `string`

***

### room?

> `optional` **room**: `string`

***

### type?

> `optional` **type**: `string`

## Methods

### listen()

> **listen**(`event`, `callback`): [`EventListenerRegister`](EventListenerRegister.md)

Subscribe to events from a specific interface on a device, such as 'OnOff' or 'Brightness'.

#### Parameters

• **event**: `string` \| [`EventListenerOptions`](EventListenerOptions.md)

• **callback**: [`EventListener`](../type-aliases/EventListener.md)

#### Returns

[`EventListenerRegister`](EventListenerRegister.md)

***

### setName()

> **setName**(`name`): `Promise`\<`void`\>

#### Parameters

• **name**: `string`

#### Returns

`Promise`\<`void`\>

***

### setRoom()

> **setRoom**(`room`): `Promise`\<`void`\>

#### Parameters

• **room**: `string`

#### Returns

`Promise`\<`void`\>

***

### setType()

> **setType**(`type`): `Promise`\<`void`\>

#### Parameters

• **type**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Returns

`Promise`\<`void`\>

***

### setMixins()

> **setMixins**(`mixins`): `Promise`\<`void`\>

#### Parameters

• **mixins**: `string`[]

#### Returns

`Promise`\<`void`\>

***

### probe()

> **probe**(): `Promise`\<`boolean`\>

Probes the device, ensuring creation of it and any mixins.

#### Returns

`Promise`\<`boolean`\>
