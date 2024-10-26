[Scrypted Documentation](../globals.md) / Setting

# Interface: Setting

## Properties

### key?

> `optional` **key**: `string`

***

### title?

> `optional` **title**: `string`

***

### group?

> `optional` **group**: `string`

***

### subgroup?

> `optional` **subgroup**: `string`

***

### description?

> `optional` **description**: `string`

***

### placeholder?

> `optional` **placeholder**: `string`

***

### type?

> `optional` **type**: `"string"` \| `"number"` \| `"boolean"` \| `"time"` \| `"button"` \| `"html"` \| `"script"` \| `"textarea"` \| `"day"` \| `"integer"` \| `"password"` \| `"device"` \| `"clippath"` \| `"interface"` \| `"date"` \| `"datetime"`

***

### range?

> `optional` **range**: [`number`, `number`]

The range of allowed numbers, if any, when the type is 'number'.

***

### readonly?

> `optional` **readonly**: `boolean`

***

### choices?

> `optional` **choices**: `string`[]

***

### combobox?

> `optional` **combobox**: `boolean`

***

### deviceFilter?

> `optional` **deviceFilter**: `string`

***

### multiple?

> `optional` **multiple**: `boolean`

***

### immediate?

> `optional` **immediate**: `boolean`

Flag that the UI should immediately apply this setting.

***

### console?

> `optional` **console**: `boolean`

Flag that hte UI should open the console.

***

### value?

> `optional` **value**: [`SettingValue`](../type-aliases/SettingValue.md)
