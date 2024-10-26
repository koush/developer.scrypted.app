[Scrypted Documentation](../globals.md) / HttpResponse

# Interface: HttpResponse

Response object provided by the HttpRequestHandler.

## Methods

### send()

#### send(body)

> **send**(`body`): `void`

##### Parameters

• **body**: `string`

##### Returns

`void`

#### send(body, options)

> **send**(`body`, `options`): `void`

##### Parameters

• **body**: `string`

• **options**: [`HttpResponseOptions`](HttpResponseOptions.md)

##### Returns

`void`

#### send(body)

> **send**(`body`): `void`

##### Parameters

• **body**: `Buffer`

##### Returns

`void`

#### send(body, options)

> **send**(`body`, `options`): `void`

##### Parameters

• **body**: `Buffer`

• **options**: [`HttpResponseOptions`](HttpResponseOptions.md)

##### Returns

`void`

***

### sendFile()

#### sendFile(path)

> **sendFile**(`path`): `void`

##### Parameters

• **path**: `string`

##### Returns

`void`

#### sendFile(path, options)

> **sendFile**(`path`, `options`): `void`

##### Parameters

• **path**: `string`

• **options**: [`HttpResponseOptions`](HttpResponseOptions.md)

##### Returns

`void`

***

### sendSocket()

> **sendSocket**(`socket`, `options`): `void`

#### Parameters

• **socket**: `any`

• **options**: [`HttpResponseOptions`](HttpResponseOptions.md)

#### Returns

`void`
