[Scrypted Documentation](../globals.md) / VideoCamera

# Interface: VideoCamera

VideoCamera devices can capture video streams.

## Methods

### getVideoStream()

> **getVideoStream**(`options`?): `Promise`\<[`MediaObject`](MediaObject.md)\>

Get a video stream.

#### Parameters

• **options?**: [`RequestMediaStreamOptions`](RequestMediaStreamOptions.md)

The media stream to fetch. If the id is specified, the exact
stream will be retrieved. Otherwise, the returned stream will be implementation
dependent.
If no options are provided at all, the implementation must return the
first stream listed in getVideoStreamOptions.

#### Returns

`Promise`\<[`MediaObject`](MediaObject.md)\>

***

### getVideoStreamOptions()

> **getVideoStreamOptions**(): `Promise`\<[`ResponseMediaStreamOptions`](ResponseMediaStreamOptions.md)[]\>

Get the available video streaming options.

#### Returns

`Promise`\<[`ResponseMediaStreamOptions`](ResponseMediaStreamOptions.md)[]\>
