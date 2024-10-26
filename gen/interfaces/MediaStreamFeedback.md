[Scrypted Documentation](../globals.md) / MediaStreamFeedback

# Interface: MediaStreamFeedback

## Methods

### onRtcp()

> **onRtcp**(`buffer`): `Promise`\<`void`\>

#### Parameters

• **buffer**: `Buffer`

#### Returns

`Promise`\<`void`\>

***

### reconfigureStream()

> **reconfigureStream**(`options`): `Promise`\<`void`\>

#### Parameters

• **options**

• **options.video**

• **options.video.bitrate?**: `number`

• **options.video.width?**: `number`

• **options.video.height?**: `number`

#### Returns

`Promise`\<`void`\>

***

### requestKeyframe()

> **requestKeyframe**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

***

### reportPacketLoss()

> **reportPacketLoss**(`report`): `Promise`\<`void`\>

#### Parameters

• **report**: [`MediaStreamPacketLoss`](MediaStreamPacketLoss.md)

#### Returns

`Promise`\<`void`\>

***

### reportPictureLoss()

> **reportPictureLoss**(): `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

***

### reportEstimatedMaxBitrate()

> **reportEstimatedMaxBitrate**(`bitrate`): `Promise`\<`void`\>

#### Parameters

• **bitrate**: `number`

#### Returns

`Promise`\<`void`\>

***

### resizeStream()

> **resizeStream**(`options`): `Promise`\<`void`\>

#### Parameters

• **options**

• **options.width**: `number`

• **options.height**: `number`

#### Returns

`Promise`\<`void`\>
