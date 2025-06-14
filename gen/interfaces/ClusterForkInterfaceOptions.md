[Scrypted Documentation](../globals.md) / ClusterForkInterfaceOptions

# Interface: ClusterForkInterfaceOptions

## Extends

- `Required`\<`Pick`\<[`ForkOptions`](ForkOptions.md), `"clusterWorkerId"`\>\>.`Pick`\<[`ForkOptions`](ForkOptions.md), `"id"` \| `"nativeId"`\>

## Properties

### id?

> `optional` **id**: `string`

The id of the device that is associated with this fork.

#### Inherited from

`Pick.id`

***

### nativeId?

> `optional` **nativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

The native id of the mixin that is associated with this fork.

#### Inherited from

`Pick.nativeId`

***

### clusterWorkerId

> **clusterWorkerId**: `string`

The id of the cluster worker id that will execute this fork.

#### Inherited from

`Required.clusterWorkerId`
