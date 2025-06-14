[Scrypted Documentation](../globals.md) / HttpResponse

# Interface: HttpResponse

Response object provided by the HttpRequestHandler.

## Methods

### send()

#### send(body, options)

> **send**(`body`, `options`?): `void`

##### Parameters

• **body**: `string`

• **options?**: [`HttpResponseOptions`](HttpResponseOptions.md)

##### Returns

`void`

#### send(body, options)

> **send**(`body`, `options`?): `void`

##### Parameters

• **body**: `Buffer`

• **options?**: [`HttpResponseOptions`](HttpResponseOptions.md)

##### Returns

`void`

***

### sendFile()

> **sendFile**(`path`, `options`?): `void`

#### Parameters

• **path**: `string`

• **options?**: [`HttpResponseOptions`](HttpResponseOptions.md)

#### Returns

`void`

***

### ~~sendSocket()~~

> **sendSocket**(`socket`, `options`?): `void`

#### Parameters

• **socket**: `any`

• **options?**: [`HttpResponseOptions`](HttpResponseOptions.md)

#### Returns

`void`

#### Deprecated

***

### sendStream()

> **sendStream**(`stream`, `options`?): `void`

#### Parameters

• **stream**: `AsyncGenerator`\<`Buffer`, `void`, `any`\>

• **options?**: [`HttpResponseOptions`](HttpResponseOptions.md)

#### Returns

`void`
