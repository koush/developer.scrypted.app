[Scrypted Documentation](../globals.md) / RequestMediaStreamOptions

# Interface: RequestMediaStreamOptions

Options passed to VideoCamera.getVideoStream to
request specific media formats.
The audio/video properties may be omitted
to indicate no audio/video is available when
calling getVideoStreamOptions or no audio/video
is requested when calling getVideoStream.

## Extends

- [`MediaStreamOptions`](MediaStreamOptions.md)

## Extended by

- [`RequestRecordingStreamOptions`](RequestRecordingStreamOptions.md)

## Properties

### id?

> `optional` **id**: `string`

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`id`](MediaStreamOptions.md#id)

***

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

### audio?

> `optional` **audio**: [`AudioStreamOptions`](AudioStreamOptions.md)

#### Inherited from

[`MediaStreamOptions`](MediaStreamOptions.md).[`audio`](MediaStreamOptions.md#audio)

***

### route?

> `optional` **route**: `"direct"` \| `"internal"` \| `"external"`

When retrieving media, setting route directs how the media should be
retrieved and exposed. A direct route will get the stream
as is from the source. This will bypass any intermediaries if possible,
such as an NVR or restreamers.
An external route will request that that provided route is exposed to the local network.

***

### refresh?

> `optional` **refresh**: `boolean`

Specify the stream refresh behavior when this stream is requested.
Use case is primarily for perioidic snapshot of streams
while they are active.

#### Default

```ts
true
```

***

### destination?

> `optional` **destination**: [`MediaStreamDestination`](../type-aliases/MediaStreamDestination.md)

The intended destination for this media stream. May be used as
a hint to determine which main/substream to send if no id
is explicitly provided.

***

### destinationId?

> `optional` **destinationId**: `string`

The destination id for this media stream. This should generally be
the IP address of the destination, if known. May be used by to
determine stream selection and track dynamic bitrate history.

***

### destinationType?

> `optional` **destinationType**: `string`

The destination type of the target of this media stream. This
should be the calling application package name. Used for logging
or adaptive bitrate fingerprinting.

***

### adaptive?

> `optional` **adaptive**: `boolean` \| [`RequestMediaStreamAdaptiveOptions`](RequestMediaStreamAdaptiveOptions.md)

Request an adaptive bitrate stream, if available. The destination
will need to report packet loss indication.

***

### video?

> `optional` **video**: [`RequestVideoStreamOptions`](RequestVideoStreamOptions.md)

#### Overrides

[`MediaStreamOptions`](MediaStreamOptions.md).[`video`](MediaStreamOptions.md#video)
