[Scrypted Documentation](../globals.md) / MediaObjectCreateOptions

# Interface: MediaObjectCreateOptions

## Extends

- [`MediaObjectOptions`](MediaObjectOptions.md)

## Indexable

 \[`key`: `string`\]: [`TopLevelSerializableType`](../type-aliases/TopLevelSerializableType.md)

## Properties

### sourceId?

> `optional` **sourceId**: `string`

The device id of the source of the MediaObject.

#### Inherited from

[`MediaObjectOptions`](MediaObjectOptions.md).[`sourceId`](MediaObjectOptions.md#sourceid)

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
