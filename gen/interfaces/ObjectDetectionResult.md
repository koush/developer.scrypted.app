[Scrypted Documentation](../globals.md) / ObjectDetectionResult

# Interface: ObjectDetectionResult

## Extends

- [`BoundingBoxResult`](BoundingBoxResult.md)

## Properties

### boundingBox?

> `optional` **boundingBox**: [`number`, `number`, `number`, `number`]

x, y, width, height

#### Inherited from

[`BoundingBoxResult`](BoundingBoxResult.md).[`boundingBox`](BoundingBoxResult.md#boundingbox)

***

### zones?

> `optional` **zones**: `string`[]

#### Inherited from

[`BoundingBoxResult`](BoundingBoxResult.md).[`zones`](BoundingBoxResult.md#zones)

***

### history?

> `optional` **history**: [`ObjectDetectionHistory`](ObjectDetectionHistory.md)

#### Inherited from

[`BoundingBoxResult`](BoundingBoxResult.md).[`history`](BoundingBoxResult.md#history)

***

### id?

> `optional` **id**: `string`

The id of the tracked object.

***

### cost?

> `optional` **cost**: `number`

The certainty that this is correct tracked object.

***

### clipped?

> `optional` **clipped**: `boolean`

Flag that indicates whether the detection was clipped by the detection input and may not be a full bounding box.

***

### className

> **className**: `string`

The detection class of the object.

***

### embedding?

> `optional` **embedding**: `string`

Base64 encoded embedding float32 vector.

***

### label?

> `optional` **label**: `string`

The label of the object, if it was recognized as a familiar object (person, pet, etc).

***

### labelScore?

> `optional` **labelScore**: `number`

The score of the label.

***

### landmarks?

> `optional` **landmarks**: [`Point`](../type-aliases/Point.md)[]

The detection landmarks, like key points in a face landmarks.

***

### clipPaths?

> `optional` **clipPaths**: [`ClipPath`](../type-aliases/ClipPath.md)[]

The detection clip paths that outlines various features or segments, like traced facial features.

***

### score

> **score**: `number`

***

### resources?

> `optional` **resources**: [`VideoResource`](VideoResource.md)

***

### movement?

> `optional` **movement**: [`ObjectDetectionHistory`](ObjectDetectionHistory.md) & `object`

Movement history will track the first/last time this object was moving.

#### Type declaration

##### moving?

> `optional` **moving**: `boolean`
