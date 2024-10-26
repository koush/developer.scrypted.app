[Scrypted Documentation](../globals.md) / OauthClient

# Interface: OauthClient

The OauthClient can be implemented to perform the browser based Oauth process from within a plugin.

## Methods

### getOauthUrl()

> **getOauthUrl**(): `Promise`\<`string`\>

Get the Oauth URL to navigate to in the browser. The redirect_uri parameter is not needed and will be automatically set by Scrypted.

#### Returns

`Promise`\<`string`\>

***

### onOauthCallback()

> **onOauthCallback**(`callbackUrl`): `Promise`\<`void`\>

When an oauth request by a plugin completes, the callback url, with the code/token, will be passed to this method.

#### Parameters

• **callbackUrl**: `string`

#### Returns

`Promise`\<`void`\>
