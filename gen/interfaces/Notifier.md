[Scrypted Documentation](../globals.md) / Notifier

# Interface: Notifier

Notifier can be any endpoint that can receive messages, such as speakers, phone numbers, messaging clients, etc. The messages may optionally contain media.

## Methods

### sendNotification()

> **sendNotification**(`title`, `options`?, `media`?, `icon`?): `Promise`\<`void`\>

#### Parameters

• **title**: `string`

• **options?**: [`NotifierOptions`](NotifierOptions.md)

• **media?**: `string` \| [`MediaObject`](MediaObject.md)

• **icon?**: `string` \| [`MediaObject`](MediaObject.md)

#### Returns

`Promise`\<`void`\>
