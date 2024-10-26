[Scrypted Documentation](../globals.md) / PasswordStore

# Interface: PasswordStore

PasswordControl represents devices that authorize users via a passcode or pin code.

## Methods

### addPassword()

> **addPassword**(`password`): `Promise`\<`void`\>

#### Parameters

• **password**: `string`

#### Returns

`Promise`\<`void`\>

***

### getPasswords()

> **getPasswords**(): `Promise`\<`string`[]\>

#### Returns

`Promise`\<`string`[]\>

***

### removePassword()

> **removePassword**(`password`): `Promise`\<`void`\>

#### Parameters

• **password**: `string`

#### Returns

`Promise`\<`void`\>
