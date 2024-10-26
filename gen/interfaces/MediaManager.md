[Scrypted Documentation](../globals.md) / MediaManager

# Interface: MediaManager

## Methods

### convertMediaObject()

> **convertMediaObject**\<`T`\>(`mediaObject`, `toMimeType`): `Promise`\<`T`\>

Convert a media object to a Buffer, primtive type, or RPC Object.

#### Type Parameters

• **T**

#### Parameters

• **mediaObject**: [`MediaObject`](MediaObject.md)

• **toMimeType**: `string`

#### Returns

`Promise`\<`T`\>

***

### convertMediaObjectToJSON()

> **convertMediaObjectToJSON**\<`T`\>(`mediaObject`, `toMimeType`): `Promise`\<`T`\>

Convert a media object to a Buffer of the given mime type, and them parse it as JSON.

#### Type Parameters

• **T**

#### Parameters

• **mediaObject**: [`MediaObject`](MediaObject.md)

• **toMimeType**: `string`

#### Returns

`Promise`\<`T`\>

***

### convertMediaObjectToBuffer()

> **convertMediaObjectToBuffer**(`mediaObject`, `toMimeType`): `Promise`\<`Buffer`\>

Convert a media object to a Buffer of the given mime type.

#### Parameters

• **mediaObject**: [`MediaObject`](MediaObject.md)

• **toMimeType**: `string`

#### Returns

`Promise`\<`Buffer`\>

***

### convertMediaObjectToInsecureLocalUrl()

> **convertMediaObjectToInsecureLocalUrl**(`mediaObject`, `toMimeType`): `Promise`\<`string`\>

Convert a media object to a locally accessible URL that serves a media file of the given mime type. If the media object is an externally accessible URL, that will be returned.

#### Parameters

• **mediaObject**: `string` \| [`MediaObject`](MediaObject.md)

• **toMimeType**: `string`

#### Returns

`Promise`\<`string`\>

***

### convertMediaObjectToLocalUrl()

> **convertMediaObjectToLocalUrl**(`mediaObject`, `toMimeType`): `Promise`\<`string`\>

Convert a media object to a locally accessible URL that serves a media file of the given mime type. If the media object is an externally accessible URL, that will be returned.

#### Parameters

• **mediaObject**: `string` \| [`MediaObject`](MediaObject.md)

• **toMimeType**: `string`

#### Returns

`Promise`\<`string`\>

***

### convertMediaObjectToUrl()

> **convertMediaObjectToUrl**(`mediaObject`, `toMimeType`): `Promise`\<`string`\>

Convert a media object to a publically accessible URL that serves a media file of the given mime type.

#### Parameters

• **mediaObject**: `string` \| [`MediaObject`](MediaObject.md)

• **toMimeType**: `string`

#### Returns

`Promise`\<`string`\>

***

### createFFmpegMediaObject()

> **createFFmpegMediaObject**\<`T`\>(`ffmpegInput`, `options`?): `Promise`\<[`MediaObject`](MediaObject.md) & `T`\>

Create a MediaObject from FFmpeg input arguments.

#### Type Parameters

• **T** *extends* [`MediaObjectCreateOptions`](MediaObjectCreateOptions.md)

#### Parameters

• **ffmpegInput**: [`FFmpegInput`](FFmpegInput.md)

• **options?**: `T`

#### Returns

`Promise`\<[`MediaObject`](MediaObject.md) & `T`\>

***

### createMediaObjectFromUrl()

> **createMediaObjectFromUrl**\<`T`\>(`data`, `options`?): `Promise`\<[`MediaObject`](MediaObject.md) & `T`\>

Create a MediaObject from an URL. The mime type will be determined dynamically while resolving the url.

#### Type Parameters

• **T** *extends* [`MediaObjectCreateOptions`](MediaObjectCreateOptions.md)

#### Parameters

• **data**: `string`

• **options?**: `T`

#### Returns

`Promise`\<[`MediaObject`](MediaObject.md) & `T`\>

***

### createMediaObject()

> **createMediaObject**\<`T`\>(`data`, `mimeType`, `options`?): `Promise`\<[`MediaObject`](MediaObject.md) & `T`\>

Create a MediaObject.
If the data is a buffer, JSON object, or primitive type, it will be serialized.
All other objects will be objects will become RPC objects.

#### Type Parameters

• **T** *extends* [`MediaObjectCreateOptions`](MediaObjectCreateOptions.md)

#### Parameters

• **data**: `any`

• **mimeType**: `string`

• **options?**: `T`

#### Returns

`Promise`\<[`MediaObject`](MediaObject.md) & `T`\>

***

### getFFmpegPath()

> **getFFmpegPath**(): `Promise`\<`string`\>

Get the path to ffmpeg on the host system.

#### Returns

`Promise`\<`string`\>

***

### getFilesPath()

> **getFilesPath**(): `Promise`\<`string`\>

Get the directory where the plugin should store files.

#### Returns

`Promise`\<`string`\>
