[Scrypted Documentation](../globals.md) / ResponseMediaStreamOptions

# Interface: ResponseMediaStreamOptions

Options passed to VideoCamera.getVideoStream to
request specific media formats.
The audio/video properties may be omitted
to indicate no audio/video is available when
calling getVideoStreamOptions or no audio/video
is requested when calling getVideoStream.

## Extends

- [`MediaStreamOptions`](MediaStreamOptions.md)

## Properties

### name?

> `optional` **name**: `string`

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`name`](MediaStreamOptions.md#name)

***

### prebuffer?

> `optional` **prebuffer**: `number`

Prebuffer time in milliseconds.

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`prebuffer`](MediaStreamOptions.md#prebuffer)

***

### prebufferBytes?

> `optional` **prebufferBytes**: `number`

Prebuffer size in bytes.

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`prebufferBytes`](MediaStreamOptions.md#prebufferbytes)

***

### container?

> `optional` **container**: `string`

The container type of this stream, ie: mp4, mpegts, rtsp.

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`container`](MediaStreamOptions.md#container)

***

### metadata?

> `optional` **metadata**: `any`

Stream specific metadata.

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`metadata`](MediaStreamOptions.md#metadata)

***

### tool?

> `optional` **tool**: [`MediaStreamTool`](../type-aliases/MediaStreamTool.md)

The tool was used to write the container or will be used to read teh container. Ie, scrypted,
the ffmpeg tools, gstreamer.

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`tool`](MediaStreamOptions.md#tool)

***

### video?

> `optional` **video**: [`VideoStreamOptions`](VideoStreamOptions.md)

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`video`](MediaStreamOptions.md#video)

***

### audio?

> `optional` **audio**: [`AudioStreamOptions`](AudioStreamOptions.md)

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`audio`](MediaStreamOptions.md#audio)

***

### id

> **id**: `string`

#### Overrides

[`MediaStreamOptions`](MediaStreamOptions.md).[`id`](MediaStreamOptions.md#id)

***

### refreshAt?

> `optional` **refreshAt**: `number`

The time in milliseconds that this stream must be refreshed again
via a call to getVideoStream.

***

### source?

> `optional` **source**: [`MediaStreamSource`](../type-aliases/MediaStreamSource.md)

***

### userConfigurable?

> `optional` **userConfigurable**: `boolean`

***

### sdp?

> `optional` **sdp**: `string`

***

### oobCodecParameters?

> `optional` **oobCodecParameters**: `boolean`

The stream's codec parameters are not contained in the stream
and are available out of band via another mechanism such as the SDP.

***

### destinations?

> `optional` **destinations**: [`MediaStreamDestination`](../type-aliases/MediaStreamDestination.md)[]

***

### allowBatteryPrebuffer?

> `optional` **allowBatteryPrebuffer**: `boolean`

Set this to true to allow for prebuffering even if the device implements the Battery interface.
Handy if you have a device that can continuously prebuffer when on mains power, but you still
want battery status reported.
