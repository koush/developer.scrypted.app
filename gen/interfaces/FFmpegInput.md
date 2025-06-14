[Scrypted Documentation](../globals.md) / FFmpegInput

# Interface: FFmpegInput

## Extends

- [`MediaContainer`](MediaContainer.md)

## Properties

### container?

> `optional` **container**: `string`

#### Inherited from

[`MediaContainer`](MediaContainer.md).[`container`](MediaContainer.md#container)

***

### mediaStreamOptions?

> `optional` **mediaStreamOptions**: [`ResponseMediaStreamOptions`](ResponseMediaStreamOptions.md)

#### Inherited from

[`MediaContainer`](MediaContainer.md).[`mediaStreamOptions`](MediaContainer.md#mediastreamoptions)

***

### url?

> `optional` **url**: `string`

The media url for this FFmpegInput.

***

### urls?

> `optional` **urls**: `string`[]

Alternate media urls for this FFmpegInput.

***

### inputArguments?

> `optional` **inputArguments**: `string`[]

***

### ~~h264EncoderArguments?~~

> `optional` **h264EncoderArguments**: `string`[]

#### Deprecated

Rebroadast use only.

***

### env?

> `optional` **env**: `object`

Environment variables to set when launching FFmpeg.

#### Index Signature

 \[`key`: `string`\]: `string`

***

### ffmpegPath?

> `optional` **ffmpegPath**: `string`

Path to a custom FFmpeg binary.
