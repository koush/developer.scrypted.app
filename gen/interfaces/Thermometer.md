[Scrypted Documentation](../globals.md) / Thermometer

# Interface: Thermometer

## Properties

### temperature?

> `optional` **temperature**: `number`

Get the ambient temperature in Celsius.

***

### temperatureUnit?

> `optional` **temperatureUnit**: [`TemperatureUnit`](../enumerations/TemperatureUnit.md)

Get the user facing unit of measurement for this thermometer, if any. Note that while this may be Fahrenheit, getTemperatureAmbient will return the temperature in Celsius.

## Methods

### setTemperatureUnit()

> **setTemperatureUnit**(`temperatureUnit`): `Promise`\<`void`\>

#### Parameters

• **temperatureUnit**: [`TemperatureUnit`](../enumerations/TemperatureUnit.md)

#### Returns

`Promise`\<`void`\>
