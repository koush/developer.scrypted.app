[Scrypted Documentation](../globals.md) / PluginFork

# Interface: PluginFork\<T\>

## Extends

- `Disposable`

## Type Parameters

• **T**

## Properties

### clusterWorkerId?

> `optional` **clusterWorkerId**: `Promise`\<`string`\>

The id of the cluster worker that is executing this fork when in cluster mode.

***

### result

> **result**: `Promise`\<`T`\>

***

### worker

> **worker**: [`ForkWorker`](ForkWorker.md)

## Methods

### \[dispose\]()

> **\[dispose\]**(): `void`

#### Returns

`void`

#### Inherited from

`Disposable.[dispose]`
