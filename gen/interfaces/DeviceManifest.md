[Scrypted Documentation](../globals.md) / DeviceManifest

# Interface: DeviceManifest

DeviceManifest is passed to DeviceManager.onDevicesChanged to sync a full list of devices from the controller/hub (Hue, SmartThings, etc)

## Properties

### providerNativeId?

> `optional` **providerNativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

The native id of the hub or discovery DeviceProvider that manages these devices.

***

### devices?

> `optional` **devices**: [`Device`](Device.md)[]
