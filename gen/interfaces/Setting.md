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

> `optional` **type**: `"string"` \| `"number"` \| `"boolean"` \| `"time"` \| `"button"` \| `"html"` \| `"script"` \| `"textarea"` \| `"day"` \| `"integer"` \| `"date"` \| `"password"` \| `"device"` \| `"clippath"` \| `"interface"` \| `"datetime"` \| `"timerange"` \| `"daterange"` \| `"datetimerange"` \| `"radiobutton"` \| `"radiopanel"`

***

### range?

> `optional` **range**: [`number`, `number`]

The range of allowed numbers or dates/times, if any, when the type is number, timerange, or daterange, or datetimerange.

***

### readonly?

> `optional` **readonly**: `boolean`

***

### choices?

> `optional` **choices**: `string`[]

***

### icon?

> `optional` **icon**: `string`

***

### icons?

> `optional` **icons**: `string`[]

***

### radioGroups?

> `optional` **radioGroups**: `string`[]

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
