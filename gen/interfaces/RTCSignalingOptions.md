[Scrypted Documentation](../globals.md) / RTCSignalingOptions

# Interface: RTCSignalingOptions

## Properties

### offer?

> `optional` **offer**: `RTCSessionDescriptionInit`

Indicates that this client requires an answer, and is providing an offer.

***

### requiresOffer?

> `optional` **requiresOffer**: `boolean`

***

### requiresAnswer?

> `optional` **requiresAnswer**: `boolean`

***

### disableTrickle?

> `optional` **disableTrickle**: `boolean`

Disables trickle ICE. All candidates must be sent in the initial offer/answer sdp.

***

### disableTurn?

> `optional` **disableTurn**: `boolean`

Disables usage of TURN servers, if this client exposes public addresses or provides its own.

***

### proxy?

> `optional` **proxy**: `boolean`

Hint to proxy the feed, as the target client may be inflexible.

***

### capabilities?

> `optional` **capabilities**: `object`

#### video?

> `optional` **video**: `RTCRtpCapabilities`

#### audio?

> `optional` **audio**: `RTCRtpCapabilities`

***

### userAgent?

> `optional` **userAgent**: `string`

***

### screen?

> `optional` **screen**: `object`

#### devicePixelRatio

> **devicePixelRatio**: `number`

#### width

> **width**: `number`

#### height

> **height**: `number`
