[Scrypted Documentation](../globals.md) / MediaPlayer

# Interface: MediaPlayer

MediaPlayer allows media playback on screen or speaker devices, such as Chromecasts or TVs.

## Methods

### getMediaStatus()

> **getMediaStatus**(): `Promise`\<[`MediaStatus`](MediaStatus.md)\>

#### Returns

`Promise`\<[`MediaStatus`](MediaStatus.md)\>

***

### load()

> **load**(`media`, `options`?): `Promise`\<`void`\>

#### Parameters

• **media**: `string` \| [`MediaObject`](MediaObject.md)

• **options?**: [`MediaPlayerOptions`](MediaPlayerOptions.md)

#### Returns

`Promise`\<`void`\>

***

### seek()

> **seek**(`milliseconds`): `Promise`\<`void`\>

#### Parameters

• **milliseconds**: `number`

#### Returns

`Promise`\<`void`\>

***

### skipNext()

> **skipNext**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

***

### skipPrevious()

> **skipPrevious**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>
