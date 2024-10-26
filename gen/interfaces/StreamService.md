[Scrypted Documentation](../globals.md) / StreamService

# Interface: StreamService\<Input, Output\>

Generic bidirectional stream connection.

## Type Parameters

• **Input**

• **Output** = `Input`

## Methods

### connectStream()

> **connectStream**(`input`?, `options`?): `Promise`\<`AsyncGenerator`\<`Output`, `void`, `unknown`\>\>

#### Parameters

• **input?**: `AsyncGenerator`\<`Input`, `void`, `unknown`\>

• **options?**: `any`

#### Returns

`Promise`\<`AsyncGenerator`\<`Output`, `void`, `unknown`\>\>
