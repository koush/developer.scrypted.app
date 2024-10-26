[Scrypted Documentation](../globals.md) / PanTiltZoomCommand

# Interface: PanTiltZoomCommand

## Properties

### movement?

> `optional` **movement**: [`PanTiltZoomMovement`](../enumerations/PanTiltZoomMovement.md)

Specify the movement type. If unspecified, the movement will be relative to the current position.

***

### pan?

> `optional` **pan**: `number`

Ranges between -1 and 1.

***

### tilt?

> `optional` **tilt**: `number`

Ranges between -1 and 1.

***

### zoom?

> `optional` **zoom**: `number`

Ranges between 0 and 1 for max zoom.

***

### speed?

> `optional` **speed**: `object`

The speed of the movement.

#### pan?

> `optional` **pan**: `number`

Ranges between 0 and 1 for max zoom.

#### tilt?

> `optional` **tilt**: `number`

Ranges between 0 and 1 for max zoom.

#### zoom?

> `optional` **zoom**: `number`

Ranges between 0 and 1 for max zoom.

***

### timeout?

> `optional` **timeout**: `number`

The duration of the movement in milliseconds.

***

### preset?

> `optional` **preset**: `string`

The preset to move to.
