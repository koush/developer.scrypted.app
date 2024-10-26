[Scrypted Documentation](../globals.md) / ResponsePictureOptions

# Interface: ResponsePictureOptions

## Extends

- [`PictureOptions`](PictureOptions.md)

## Properties

### id?

> `optional` **id**: `string`

#### Inherited from

[`PictureOptions`](PictureOptions.md).[`id`](PictureOptions.md#id)

***

### picture?

> `optional` **picture**: [`PictureDimensions`](PictureDimensions.md)

The native dimensions of the camera.

#### Inherited from

[`PictureOptions`](PictureOptions.md).[`picture`](PictureOptions.md#picture)

***

### name?

> `optional` **name**: `string`

***

### canResize?

> `optional` **canResize**: `boolean`

Flag that indicates that the request supports resizing to custom dimensions.

***

### staleDuration?

> `optional` **staleDuration**: `number`

Flag that indicates the camera will return a stale/cached image.
