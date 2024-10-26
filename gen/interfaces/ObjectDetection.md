[Scrypted Documentation](../globals.md) / ObjectDetection

# Interface: ObjectDetection

ObjectDetection can run classifications or analysis on arbitrary media sources.
E.g. TensorFlow, OpenCV, or a Coral TPU.

## Methods

### generateObjectDetections()

> **generateObjectDetections**(`videoFrames`, `session`): `Promise`\<`AsyncGenerator`\<[`ObjectDetectionGeneratorResult`](ObjectDetectionGeneratorResult.md), `void`, `unknown`\>\>

#### Parameters

• **videoFrames**: [`MediaObject`](MediaObject.md) \| `AsyncGenerator`\<[`VideoFrame`](VideoFrame.md), `void`, `unknown`\>

• **session**: [`ObjectDetectionGeneratorSession`](ObjectDetectionGeneratorSession.md)

#### Returns

`Promise`\<`AsyncGenerator`\<[`ObjectDetectionGeneratorResult`](ObjectDetectionGeneratorResult.md), `void`, `unknown`\>\>

***

### detectObjects()

> **detectObjects**(`mediaObject`, `session`?): `Promise`\<[`ObjectsDetected`](ObjectsDetected.md)\>

#### Parameters

• **mediaObject**: [`MediaObject`](MediaObject.md)

• **session?**: [`ObjectDetectionSession`](ObjectDetectionSession.md)

#### Returns

`Promise`\<[`ObjectsDetected`](ObjectsDetected.md)\>

***

### getDetectionModel()

> **getDetectionModel**(`settings`?): `Promise`\<[`ObjectDetectionModel`](ObjectDetectionModel.md)\>

#### Parameters

• **settings?**

#### Returns

`Promise`\<[`ObjectDetectionModel`](ObjectDetectionModel.md)\>
