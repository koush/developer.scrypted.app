[Scrypted Documentation](../globals.md) / Logger

# Interface: Logger

Logger is exposed via log.* to allow writing to the Scrypted log.

## Methods

### a()

> **a**(`msg`): `void`

Alert. Alert level logs will be displayed as a notification in the management console.

#### Parameters

• **msg**: `string`

#### Returns

`void`

***

### clear()

> **clear**(): `void`

Clear the log

#### Returns

`void`

***

### clearAlert()

> **clearAlert**(`msg`): `void`

Clear a specific alert

#### Parameters

• **msg**: `string`

#### Returns

`void`

***

### clearAlerts()

> **clearAlerts**(): `void`

Clear all alerts

#### Returns

`void`

***

### d()

> **d**(`msg`): `void`

Debug

#### Parameters

• **msg**: `string`

#### Returns

`void`

***

### e()

> **e**(`msg`): `void`

Error

#### Parameters

• **msg**: `string`

#### Returns

`void`

***

### i()

> **i**(`msg`): `void`

Info

#### Parameters

• **msg**: `string`

#### Returns

`void`

***

### v()

> **v**(`msg`): `void`

Verbose

#### Parameters

• **msg**: `string`

#### Returns

`void`

***

### w()

> **w**(`msg`): `void`

Warn

#### Parameters

• **msg**: `string`

#### Returns

`void`
