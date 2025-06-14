[Scrypted Documentation](../globals.md) / MixinProvider

# Interface: MixinProvider

MixinProviders can add and intercept interfaces to other devices to add or augment their behavior.

## Methods

### canMixin()

> **canMixin**(`type`, `interfaces`): `Promise`\<`undefined` \| `null` \| `void` \| `string`[]\>

Called by the system to determine if this provider can create a mixin for the supplied device. Returns null if a mixin can not be created, otherwise returns a list of new interfaces (which may be an empty list) that are provided by the mixin.

#### Parameters

• **type**: `string`

• **interfaces**: `string`[]

#### Returns

`Promise`\<`undefined` \| `null` \| `void` \| `string`[]\>

***

### getMixin()

> **getMixin**(`mixinDevice`, `mixinDeviceInterfaces`, `mixinDeviceState`): `Promise`\<`any`\>

Create a mixin that can be applied to the supplied device.

#### Parameters

• **mixinDevice**: `any`

• **mixinDeviceInterfaces**: [`ScryptedInterface`](../enumerations/ScryptedInterface.md)[]

• **mixinDeviceState**: [`WritableDeviceState`](WritableDeviceState.md)

#### Returns

`Promise`\<`any`\>

***

### releaseMixin()

> **releaseMixin**(`id`, `mixinDevice`): `Promise`\<`void`\>

Release a mixin device that was previously returned from getMixin.

#### Parameters

• **id**: `string`

• **mixinDevice**: `any`

#### Returns

`Promise`\<`void`\>
