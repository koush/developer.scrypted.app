[Scrypted Documentation](../globals.md) / Device

# Interface: Device

Device objects are created by DeviceProviders when new devices are discover and synced to Scrypted via the DeviceManager.

## Properties

### name

> **name**: `string`

***

### nativeId

> **nativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

The native id that is used by the DeviceProvider used to internally identify provided devices.

***

### type

> **type**: `string`

***

### interfaces

> **interfaces**: `string`[]

***

### info?

> `optional` **info**: [`DeviceInformation`](DeviceInformation.md)

***

### providerNativeId?

> `optional` **providerNativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

The native id of the hub or discovery DeviceProvider that manages this device.

***

### room?

> `optional` **room**: `string`

***

### refresh?

> `optional` **refresh**: `boolean`

Directs Scrypted to purge any previously returned instances of the device and call getDevice on the DeviceProvider.
