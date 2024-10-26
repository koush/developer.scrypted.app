[Scrypted Documentation](../globals.md) / ObjectDetector

# Interface: ObjectDetector

ObjectDetector is found on Cameras that have smart detection capabilities.

## Methods

### getDetectionInput()

> **getDetectionInput**(`detectionId`, `eventId`?): `Promise`\<[`MediaObject`](MediaObject.md)\>

Get the media (image or video) that contains this detection.

#### Parameters

• **detectionId**: `string`

• **eventId?**: `any`

#### Returns

`Promise`\<[`MediaObject`](MediaObject.md)\>

***

### getObjectTypes()

> **getObjectTypes**(): `Promise`\<[`ObjectDetectionTypes`](ObjectDetectionTypes.md)\>

#### Returns

`Promise`\<[`ObjectDetectionTypes`](ObjectDetectionTypes.md)\>
