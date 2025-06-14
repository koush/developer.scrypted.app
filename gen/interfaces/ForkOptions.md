[Scrypted Documentation](../globals.md) / ForkOptions

# Interface: ForkOptions

## Properties

### name?

> `optional` **name**: `string`

The name of this fork. This will be used to set the thread name

***

### runtime?

> `optional` **runtime**: `string`

The runtime to use for this fork. If not specified, the current runtime will be used.

***

### filename?

> `optional` **filename**: `string`

The filename to execute in the fork. Not supported in all runtimes.

***

### id?

> `optional` **id**: `string`

The id of the device that is associated with this fork.

***

### nativeId?

> `optional` **nativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

The native id of the mixin that is associated with this fork.

***

### clusterWorkerId?

> `optional` **clusterWorkerId**: `string`

The id of the cluster worker id that will execute this fork.

***

### labels?

> `optional` **labels**: `object`

The labels used to select the cluster worker that will execute this fork.

#### require?

> `optional` **require**: `string`[]

The worker must have all these labels.

#### any?

> `optional` **any**: `string`[]

The worker must have one of these labels.

#### prefer?

> `optional` **prefer**: `string`[]

The worker is preferred to have one of these labels.
The nearest match will be selected.
