[Scrypted Documentation](../globals.md) / RTCSignalingSession

# Interface: RTCSignalingSession

Implemented by WebRTC cameras to negotiate a peer connection session with Scrypted.

## Properties

### \_\_proxy\_props

> **\_\_proxy\_props**: `object`

#### options

> **options**: [`RTCSignalingOptions`](RTCSignalingOptions.md)

***

### options

> **options**: [`RTCSignalingOptions`](RTCSignalingOptions.md)

## Methods

### createLocalDescription()

> **createLocalDescription**(`type`, `setup`, `sendIceCandidate`): `Promise`\<`RTCSessionDescriptionInit`\>

#### Parameters

• **type**: `"answer"` \| `"offer"`

• **setup**: [`RTCAVSignalingSetup`](RTCAVSignalingSetup.md)

• **sendIceCandidate**: `undefined` \| [`RTCSignalingSendIceCandidate`](../type-aliases/RTCSignalingSendIceCandidate.md)

#### Returns

`Promise`\<`RTCSessionDescriptionInit`\>

***

### setRemoteDescription()

> **setRemoteDescription**(`description`, `setup`): `Promise`\<`void`\>

#### Parameters

• **description**: `RTCSessionDescriptionInit`

• **setup**: [`RTCAVSignalingSetup`](RTCAVSignalingSetup.md)

#### Returns

`Promise`\<`void`\>

***

### addIceCandidate()

> **addIceCandidate**(`candidate`): `Promise`\<`void`\>

#### Parameters

• **candidate**: `RTCIceCandidateInit`

#### Returns

`Promise`\<`void`\>

***

### ~~getOptions()~~

> **getOptions**(): `Promise`\<[`RTCSignalingOptions`](RTCSignalingOptions.md)\>

#### Returns

`Promise`\<[`RTCSignalingOptions`](RTCSignalingOptions.md)\>

#### Deprecated
