[Scrypted Documentation](../globals.md) / Image

# Interface: Image

## Properties

### width

> **width**: `number`

***

### height

> **height**: `number`

***

### format?

> `optional` **format**: [`ImageFormat`](../type-aliases/ImageFormat.md)

The in raw memory format of this image.
Operations of this image may only safely request
this format, or a compressed format such as jpg.

## Methods

### toBuffer()

> **toBuffer**(`options`?): `Promise`\<`Buffer`\>

#### Parameters

• **options?**: [`ImageOptions`](ImageOptions.md)

#### Returns

`Promise`\<`Buffer`\>

***

### toImage()

> **toImage**(`options`?): `Promise`\<[`Image`](Image.md) & [`MediaObject`](MediaObject.md)\>

#### Parameters

• **options?**: [`ImageOptions`](ImageOptions.md)

#### Returns

`Promise`\<[`Image`](Image.md) & [`MediaObject`](MediaObject.md)\>

***

### close()

> **close**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>
