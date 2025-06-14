[Scrypted Documentation](../globals.md) / ClusterFork

# Interface: ClusterFork

## Properties

### runtime?

> `optional` **runtime**: `string`

***

### labels?

> `optional` **labels**: `object`

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

***

### id?

> `optional` **id**: `string`

***

### clusterWorkerId

> **clusterWorkerId**: `undefined` \| `string`
