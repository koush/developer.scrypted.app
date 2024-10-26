[Scrypted Documentation](../globals.md) / ObjectDetectionModel

# Interface: ObjectDetectionModel

## Extends

- [`ObjectDetectionTypes`](ObjectDetectionTypes.md)

## Properties

### classes?

> `optional` **classes**: `string`[]

Classes of objects that can be recognized. This can include motion
or the names of specific people.

#### Inherited from

[`ObjectDetectionTypes`](ObjectDetectionTypes.md).[`classes`](ObjectDetectionTypes.md#classes)

***

### name

> **name**: `string`

***

### inputSize?

> `optional` **inputSize**: `number`[]

***

### inputFormat?

> `optional` **inputFormat**: `"rgb"` \| `"gray"` \| `"rgba"`

***

### settings

> **settings**: [`Setting`](Setting.md)[]

***

### triggerClasses?

> `optional` **triggerClasses**: `string`[]

***

### prebuffer?

> `optional` **prebuffer**: `number`

***

### decoder?

> `optional` **decoder**: `boolean`
