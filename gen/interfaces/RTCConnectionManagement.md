[Scrypted Documentation](../globals.md) / RTCConnectionManagement

# Interface: RTCConnectionManagement

## Methods

### negotiateRTCSignalingSession()

> **negotiateRTCSignalingSession**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

***

### addTrack()

> **addTrack**(`mediaObject`, `options`?): `Promise`\<[`RTCOutputMediaObjectTrack`](RTCOutputMediaObjectTrack.md)\>

#### Parameters

• **mediaObject**: [`MediaObject`](MediaObject.md)

• **options?**

• **options.videoMid?**: `string`

• **options.audioMid?**: `string`

• **options.intercomId?**: `string`

**Deprecated**

#### Returns

`Promise`\<[`RTCOutputMediaObjectTrack`](RTCOutputMediaObjectTrack.md)\>

***

### addInputTrack()

> **addInputTrack**(`options`): `Promise`\<[`RTCInputMediaObjectTrack`](RTCInputMediaObjectTrack.md)\>

#### Parameters

• **options**

• **options.videoMid?**: `string`

• **options.audioMid?**: `string`

#### Returns

`Promise`\<[`RTCInputMediaObjectTrack`](RTCInputMediaObjectTrack.md)\>

***

### close()

> **close**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

***

### probe()

> **probe**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>
