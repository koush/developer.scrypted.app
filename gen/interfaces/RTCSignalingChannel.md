[Scrypted Documentation](../globals.md) / RTCSignalingChannel

# Interface: RTCSignalingChannel

An inflexible RTC Signaling channel, typically a vendor, like Nest or Ring.
They generally can only handle either offer or answer, but not both. Usually has
strict requirements and expectations on client setup.

## Methods

### startRTCSignalingSession()

> **startRTCSignalingSession**(`session`): `Promise`\<`undefined` \| [`RTCSessionControl`](RTCSessionControl.md)\>

#### Parameters

• **session**: [`RTCSignalingSession`](RTCSignalingSession.md)

#### Returns

`Promise`\<`undefined` \| [`RTCSessionControl`](RTCSessionControl.md)\>
