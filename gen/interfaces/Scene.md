[Scrypted Documentation](../globals.md) / Scene

# Interface: Scene

Scenes control multiple different devices into a given state.

## Methods

### activate()

> **activate**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

***

### deactivate()

> **deactivate**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

***

### isReversible()

> **isReversible**(): `boolean`

If a scene can be reversed, isReversible should return true. Otherwise deactivate will not be called.

#### Returns

`boolean`
