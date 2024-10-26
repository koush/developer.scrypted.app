[Scrypted Documentation](../globals.md) / VideoClips

# Interface: VideoClips

## Methods

### getVideoClips()

> **getVideoClips**(`options`?): `Promise`\<[`VideoClip`](VideoClip.md)[]\>

#### Parameters

• **options?**: [`VideoClipOptions`](VideoClipOptions.md)

#### Returns

`Promise`\<[`VideoClip`](VideoClip.md)[]\>

***

### getVideoClip()

> **getVideoClip**(`videoId`): `Promise`\<[`MediaObject`](MediaObject.md)\>

#### Parameters

• **videoId**: `string`

#### Returns

`Promise`\<[`MediaObject`](MediaObject.md)\>

***

### getVideoClipThumbnail()

> **getVideoClipThumbnail**(`thumbnailId`, `options`?): `Promise`\<[`MediaObject`](MediaObject.md)\>

#### Parameters

• **thumbnailId**: `string`

• **options?**: [`VideoClipThumbnailOptions`](VideoClipThumbnailOptions.md)

#### Returns

`Promise`\<[`MediaObject`](MediaObject.md)\>

***

### removeVideoClips()

> **removeVideoClips**(...`videoClipIds`): `Promise`\<`void`\>

#### Parameters

• ...**videoClipIds**: `string`[]

#### Returns

`Promise`\<`void`\>
