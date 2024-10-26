[Scrypted Documentation](../globals.md) / Refresh

# Interface: Refresh

Refresh indicates that this device has properties that are not automatically updated, and must be periodically refreshed via polling. Device implementations should never implement their own underlying polling algorithm, and instead implement Refresh to allow Scrypted to manage polling intelligently.

## Methods

### getRefreshFrequency()

> **getRefreshFrequency**(): `Promise`\<`number`\>

Get the recommended refresh/poll frequency in seconds for this device.

#### Returns

`Promise`\<`number`\>

***

### refresh()

> **refresh**(`refreshInterface`, `userInitiated`): `Promise`\<`void`\>

This method is called by Scrypted when the properties of the device need to be refreshed. When the device has completed the refresh, the appropriate DeviceState properties should be set. The parameters provide the specific interface that needs to be refreshed and whether it was user initiated (via UI or voice).

#### Parameters

• **refreshInterface**: `string`

• **userInitiated**: `boolean`

#### Returns

`Promise`\<`void`\>
