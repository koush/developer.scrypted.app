[Scrypted Documentation](../globals.md) / BufferConverter

# Interface: ~~BufferConverter~~

Add a converter to be used by Scrypted to convert buffers from one mime type to another mime type.
May optionally accept string urls if accept-url is a fromMimeType parameter.

## Deprecated

## Properties

### ~~fromMimeType?~~

> `optional` **fromMimeType**: `string`

***

### ~~toMimeType?~~

> `optional` **toMimeType**: `string`

## Methods

### ~~convert()~~

> **convert**(`data`, `fromMimeType`, `toMimeType`, `options`?): `Promise`\<`any`\>

#### Parameters

• **data**: `any`

• **fromMimeType**: `string`

• **toMimeType**: `string`

• **options?**: [`MediaObjectOptions`](MediaObjectOptions.md)

#### Returns

`Promise`\<`any`\>
