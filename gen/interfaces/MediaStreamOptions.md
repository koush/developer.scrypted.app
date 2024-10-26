[Scrypted Documentation](../globals.md) / MediaStreamOptions

# Interface: MediaStreamOptions

Options passed to VideoCamera.getVideoStream to
request specific media formats.
The audio/video properties may be omitted
to indicate no audio/video is available when
calling getVideoStreamOptions or no audio/video
is requested when calling getVideoStream.

## Extended by

- [`ResponseMediaStreamOptions`](ResponseMediaStreamOptions.md)
- [`RequestMediaStreamOptions`](RequestMediaStreamOptions.md)

## Properties

### id?

> `optional` **id**: `string`

***

### name?

> `optional` **name**: `string`

***

### prebuffer?

> `optional` **prebuffer**: `number`

Prebuffer time in milliseconds.

***

### prebufferBytes?

> `optional` **prebufferBytes**: `number`

Prebuffer size in bytes.

***

### container?

> `optional` **container**: `string`

The container type of this stream, ie: mp4, mpegts, rtsp.

***

### metadata?

> `optional` **metadata**: `any`

Stream specific metadata.

***

### tool?

> `optional` **tool**: [`MediaStreamTool`](../type-aliases/MediaStreamTool.md)

The tool was used to write the container or will be used to read teh container. Ie, scrypted,
the ffmpeg tools, gstreamer.

***

### video?

> `optional` **video**: [`VideoStreamOptions`](VideoStreamOptions.md)

***

### audio?

> `optional` **audio**: [`AudioStreamOptions`](AudioStreamOptions.md)
