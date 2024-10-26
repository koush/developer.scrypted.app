[Scrypted Documentation](../globals.md) / ScryptedStatic

# Interface: ScryptedStatic

## Properties

### ~~log?~~

> `optional` **log**: [`Logger`](Logger.md)

#### Deprecated

***

### deviceManager

> **deviceManager**: [`DeviceManager`](DeviceManager.md)

***

### endpointManager

> **endpointManager**: [`EndpointManager`](EndpointManager.md)

***

### mediaManager

> **mediaManager**: [`MediaManager`](MediaManager.md)

***

### systemManager

> **systemManager**: [`SystemManager`](SystemManager.md)

***

### serverVersion?

> `optional` **serverVersion**: `string`

***

### pluginHostAPI

> **pluginHostAPI**: `any`

***

### pluginRemoteAPI

> **pluginRemoteAPI**: `any`

## Methods

### fork()

> **fork**\<`T`\>(`options`?): [`PluginFork`](PluginFork.md)\<`T`\>

Start a new instance of the plugin, returning an instance of the new process
and the result of the fork method.

#### Type Parameters

• **T**

#### Parameters

• **options?**: [`ForkOptions`](ForkOptions.md)

#### Returns

[`PluginFork`](PluginFork.md)\<`T`\>

***

### connect()

> **connect**(`socket`, `options`?): `void`

Initiate the Scrypted RPC wire protocol on a socket.

#### Parameters

• **socket**: `Socket`

• **options?**: [`ConnectOptions`](ConnectOptions.md)

#### Returns

`void`

***

### connectRPCObject()

> **connectRPCObject**\<`T`\>(`value`): `Promise`\<`T`\>

Attempt to retrieve an RPC object by directly connecting to the plugin
that created the object. All operations on this object will bypass routing
through the Scrypted Server which typically manages plugin communication.
This is ideal for sending large amounts of data.

#### Type Parameters

• **T**

#### Parameters

• **value**: `T`

#### Returns

`Promise`\<`T`\>
