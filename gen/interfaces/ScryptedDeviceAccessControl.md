[Scrypted Documentation](../globals.md) / ScryptedDeviceAccessControl

# Interface: ScryptedDeviceAccessControl

ScryptedDeviceAccessControl describes the methods and properties on a device
that will be visible to the user.
If methods is nullish, the user will be granted full access to all methods.
If properties is nullish, the user will be granted full access to all properties.
If events is nullish, the user will be granted full access to all events.

## Properties

### id

> **id**: `string`

***

### methods?

> `optional` **methods**: `string`[]

***

### properties?

> `optional` **properties**: `string`[]

***

### interfaces?

> `optional` **interfaces**: `string`[]
