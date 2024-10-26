[Scrypted Documentation](../globals.md) / HttpRequestHandler

# Interface: HttpRequestHandler

The HttpRequestHandler allows handling of web requests under the endpoint path: /endpoint/npm-package-name/*.

## Methods

### onRequest()

> **onRequest**(`request`, `response`): `Promise`\<`void`\>

Callback to handle an incoming request.

#### Parameters

• **request**: [`HttpRequest`](HttpRequest.md)

• **response**: [`HttpResponse`](HttpResponse.md)

#### Returns

`Promise`\<`void`\>
