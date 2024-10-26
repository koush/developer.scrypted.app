[Scrypted Documentation](../globals.md) / EventListenerOptions

# Interface: EventListenerOptions

## Properties

### denoise?

> `optional` **denoise**: `boolean`

This EventListener will denoise events, and will not be called unless the state changes.

***

### event?

> `optional` **event**: `string`

The EventListener will subscribe to this event interface.

***

### watch?

> `optional` **watch**: `boolean`

This EventListener will passively watch for events, and not initiate polling.

***

### mixinId?

> `optional` **mixinId**: `string`

The EventListener will listen to events and property changes from a device or mixin that is suppressed by a mixin.
