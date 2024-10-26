[Scrypted Documentation](../globals.md) / MediaObject

# Interface: MediaObject

MediaObject is an intermediate object within Scrypted to represent all media objects. Plugins should use the MediaConverter to convert the Scrypted MediaObject into a desired type, whether it is a externally accessible URL, a Buffer, etc.

## Properties

### mimeType

> **mimeType**: `string`

***

### sourceId?

> `optional` **sourceId**: `string`

***

### toMimeTypes?

> `optional` **toMimeTypes**: `string`[]

## Methods

### convert()?

> `optional` **convert**\<`T`\>(`toMimeType`): `Promise`\<`T`\>

#### Type Parameters

• **T**

#### Parameters

• **toMimeType**: `string`

#### Returns

`Promise`\<`T`\>
