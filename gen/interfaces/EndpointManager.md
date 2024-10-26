[Scrypted Documentation](../globals.md) / EndpointManager

# Interface: EndpointManager

EndpointManager provides publicly accessible URLs that can be used to contact your Scrypted Plugin.

## Methods

### ~~getAuthenticatedPath()~~

> **getAuthenticatedPath**(`nativeId`?): `Promise`\<`string`\>

Get an URL pathname for a device that can be accessed with authentication. This is a relative path that can be used in browser sessions.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Promise`\<`string`\>

#### Deprecated

***

### ~~getInsecurePublicLocalEndpoint()~~

> **getInsecurePublicLocalEndpoint**(`nativeId`?): `Promise`\<`string`\>

Get an URL that can only be accessed on your local network by anyone with the link. HTTP requests and responses are without any encryption. Plugin implementation is responsible for authentication.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Promise`\<`string`\>

#### Deprecated

***

### ~~getPublicLocalEndpoint()~~

> **getPublicLocalEndpoint**(`nativeId`?): `Promise`\<`string`\>

Get an URL that can only be accessed on your local network by anyone with the link. HTTP requests and responses are over SSL with a self signed certificate. Plugin implementation is responsible for authentication.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Promise`\<`string`\>

#### Deprecated

***

### ~~getPublicPushEndpoint()~~

> **getPublicPushEndpoint**(`nativeId`?): `Promise`\<`string`\>

Get an URL that can be used to send a push message to the client. This differs from a cloud endpoint, in that, the Plugin does not send a response back. Plugin implementation is responsible for authentication.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Promise`\<`string`\>

#### Deprecated

***

### ~~getPublicCloudEndpoint()~~

> **getPublicCloudEndpoint**(`nativeId`?): `Promise`\<`string`\>

Get an URL that can be externally accessed by anyone with the link. Plugin implementation is responsible for authentication.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Promise`\<`string`\>

#### Deprecated

***

### getPath()

> **getPath**(`nativeId`?, `options`?): `Promise`\<`string`\>

Get an URL pathname for a device. This is a relative path that can be used in browser sessions.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

• **options?**

• **options.public?**: `boolean`

A public endpoint that does not require authentication with the local Scrypted server.

#### Returns

`Promise`\<`string`\>

***

### getLocalEndpoint()

> **getLocalEndpoint**(`nativeId`?, `options`?): `Promise`\<`string`\>

Get an URL that can only be accessed on your local network by anyone with the link.

#### Parameters

• **nativeId?**: `string`

• **options?**

• **options.public?**: `boolean`

A public endpoint that does not require authentication with the local Scrypted server.

• **options.insecure?**: `boolean`

An insecure endpoint served by http, not https.

#### Returns

`Promise`\<`string`\>

***

### getCloudEndpoint()

> **getCloudEndpoint**(`nativeId`?, `options`?): `Promise`\<`string`\>

Get an URL that can be externally accessed by anyone with the link. Plugin implementation is responsible for authentication.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

• **options?**

• **options.public?**: `boolean`

A public endpoint that does not require authentication with the local Scrypted server.

#### Returns

`Promise`\<`string`\>

***

### getCloudPushEndpoint()

> **getCloudPushEndpoint**(`nativeId`?): `Promise`\<`string`\>

Get an URL that can be used to send a push message to the client. This differs from a cloud endpoint, in that, the Plugin does not send a response back.

#### Parameters

• **nativeId?**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

#### Returns

`Promise`\<`string`\>

***

### setLocalAddresses()

> **setLocalAddresses**(`addresses`): `Promise`\<`void`\>

Set the recommended local addresses used by Scrypted plugins that listen for incoming connections.

#### Parameters

• **addresses**: `string`[]

#### Returns

`Promise`\<`void`\>

***

### getLocalAddresses()

> **getLocalAddresses**(): `Promise`\<`string`[]\>

Get the recommended local addresess used by Scrypted plugins that listen for incoming connections.

#### Returns

`Promise`\<`string`[]\>

***

### setAccessControlAllowOrigin()

> **setAccessControlAllowOrigin**(`options`): `Promise`\<`void`\>

Set the allowed origins for an endpoint for cross origin requests.
I.e. 'https://example.com' would allow cross origin requests from that origin.
For security, this setting will not persist between plugin reloads and must
be called per desired origin after plugin startup.

#### Parameters

• **options**: [`EndpointAccessControlAllowOrigin`](EndpointAccessControlAllowOrigin.md)

#### Returns

`Promise`\<`void`\>
