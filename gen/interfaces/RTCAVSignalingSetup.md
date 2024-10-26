[Scrypted Documentation](../globals.md) / RTCAVSignalingSetup

# Interface: RTCAVSignalingSetup

## Properties

### configuration?

> `optional` **configuration**: `RTCConfiguration`

Mechanism to allow configuration of TURN/STUN servers, etc.

***

### audio?

> `optional` **audio**: `RTCRtpTransceiverInit`

***

### video?

> `optional` **video**: `RTCRtpTransceiverInit`

***

### getUserMediaSafariHack?

> `optional` **getUserMediaSafariHack**: `boolean`

Some endpoints like Ring do not stream to Safari unless getUserMedia is called. Unclear why.

***

### datachannel?

> `optional` **datachannel**: `object`

#### label

> **label**: `string`

#### dict?

> `optional` **dict**: `RTCDataChannelInit`

***

### type

> **type**: `"answer"` \| `"offer"`
