[Scrypted Documentation](../globals.md) / ClusterManager

# Interface: ClusterManager

## Methods

### getClusterWorkerId()

> **getClusterWorkerId**(): `string`

Returns the id of this cluster worker.
Returns undefined if this is not a cluster worker.

#### Returns

`string`

***

### getClusterAddress()

> **getClusterAddress**(): `string`

#### Returns

`string`

***

### getClusterMode()

> **getClusterMode**(): `undefined` \| `"server"` \| `"client"`

#### Returns

`undefined` \| `"server"` \| `"client"`

***

### getClusterWorkers()

> **getClusterWorkers**(): `Promise`\<`Record`\<`string`, [`ClusterWorker`](ClusterWorker.md)\>\>

#### Returns

`Promise`\<`Record`\<`string`, [`ClusterWorker`](ClusterWorker.md)\>\>
