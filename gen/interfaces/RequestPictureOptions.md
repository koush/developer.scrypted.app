[Scrypted Documentation](../globals.md) / RequestPictureOptions

# Interface: RequestPictureOptions

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

### reason?

> `optional` **reason**: `"event"` \| `"periodic"`

periodic: The requestor will request the snapshot periodically so a recent cached image may be returned.
event: The requestor needs an image for event processing or thumbnail. Cached or error images will not be returned.

***

### periodicRequest?

> `optional` **periodicRequest**: `boolean`

Flag that hints whether this user request is happening due to a periodic refresh.

***

### bulkRequest?

> `optional` **bulkRequest**: `boolean`

Flag that hints whether multiple cameras are being refreshed by this user request. Can be used to prefetch the snapshots.

***

### timeout?

> `optional` **timeout**: `number`

The maximum time in milliseconds to wait for the picture.
