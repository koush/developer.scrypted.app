[Scrypted Documentation](../globals.md) / VideoRecorder

# Interface: VideoRecorder

## Properties

### recordingActive?

> `optional` **recordingActive**: `boolean`

## Methods

### getRecordingStream()

> **getRecordingStream**(`options`, `recordingStream`?): `Promise`\<[`MediaObject`](MediaObject.md)\>

Returns a MediaObject for a recording stream.

#### Parameters

• **options**: [`RequestRecordingStreamOptions`](RequestRecordingStreamOptions.md)

Options that denote where to start the recording stream.
If a duration is specified, a downloadable stream will be returned.
If a duration is not specified, a playback stream will be returned.

• **recordingStream?**: [`MediaObject`](MediaObject.md)

Optionally provide a previously returned recording stream
to seek to a new position within that stream. If the seek is successful, the previous
MediaObject will update its playback position and no MediaObject will be returned.

#### Returns

`Promise`\<[`MediaObject`](MediaObject.md)\>

***

### getRecordingStreamCurrentTime()

> **getRecordingStreamCurrentTime**(`recordingStream`): `Promise`\<`number`\>

#### Parameters

• **recordingStream**: [`MediaObject`](MediaObject.md)

#### Returns

`Promise`\<`number`\>

***

### getRecordingStreamOptions()

> **getRecordingStreamOptions**(): `Promise`\<[`ResponseMediaStreamOptions`](ResponseMediaStreamOptions.md)[]\>

#### Returns

`Promise`\<[`ResponseMediaStreamOptions`](ResponseMediaStreamOptions.md)[]\>

***

### getRecordingStreamThumbnail()

> **getRecordingStreamThumbnail**(`time`, `options`?): `Promise`\<[`MediaObject`](MediaObject.md)\>

#### Parameters

• **time**: `number`

• **options?**: [`RecordingStreamThumbnailOptions`](RecordingStreamThumbnailOptions.md)

#### Returns

`Promise`\<[`MediaObject`](MediaObject.md)\>
