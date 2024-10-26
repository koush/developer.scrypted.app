[Scrypted Documentation](../globals.md) / DeviceState

# Interface: DeviceState

## Extended by

- [`WritableDeviceState`](WritableDeviceState.md)

## Properties

### id

> **id**: `string`

***

### info?

> `optional` **info**: [`DeviceInformation`](DeviceInformation.md)

***

### interfaces

> **interfaces**: `string`[]

***

### mixins

> **mixins**: `string`[]

***

### name?

> `optional` **name**: `string`

***

### nativeId?

> `optional` **nativeId**: `string`

***

### pluginId

> **pluginId**: `string`

***

### providedInterfaces

> **providedInterfaces**: `string`[]

***

### providedName?

> `optional` **providedName**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

***

### providedRoom?

> `optional` **providedRoom**: `string`

***

### providedType?

> `optional` **providedType**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

***

### providerId?

> `optional` **providerId**: `string`

***

### room?

> `optional` **room**: `string`

***

### type?

> `optional` **type**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

***

### scryptedRuntimeArguments?

> `optional` **scryptedRuntimeArguments**: [`ScryptedRuntimeArguments`](ScryptedRuntimeArguments.md)

***

### on?

> `optional` **on**: `boolean`

***

### brightness?

> `optional` **brightness**: `number`

***

### colorTemperature?

> `optional` **colorTemperature**: `number`

***

### rgb?

> `optional` **rgb**: [`ColorRgb`](ColorRgb.md)

***

### hsv?

> `optional` **hsv**: [`ColorHsv`](ColorHsv.md)

***

### running?

> `optional` **running**: `boolean`

***

### paused?

> `optional` **paused**: `boolean`

***

### docked?

> `optional` **docked**: `boolean`

***

### temperatureSetting?

> `optional` **temperatureSetting**: [`TemperatureSettingStatus`](TemperatureSettingStatus.md)

***

### temperature?

> `optional` **temperature**: `number`

***

### temperatureUnit?

> `optional` **temperatureUnit**: [`TemperatureUnit`](../enumerations/TemperatureUnit.md)

***

### humidity?

> `optional` **humidity**: `number`

***

### audioVolumes?

> `optional` **audioVolumes**: [`AudioVolumes`](AudioVolumes.md)

***

### recordingActive?

> `optional` **recordingActive**: `boolean`

***

### ptzCapabilities?

> `optional` **ptzCapabilities**: [`PanTiltZoomCapabilities`](PanTiltZoomCapabilities.md)

***

### lockState?

> `optional` **lockState**: [`LockState`](../enumerations/LockState.md)

***

### entryOpen?

> `optional` **entryOpen**: `boolean` \| `"jammed"`

***

### batteryLevel?

> `optional` **batteryLevel**: `number`

***

### chargeState?

> `optional` **chargeState**: [`ChargeState`](../enumerations/ChargeState.md)

***

### online?

> `optional` **online**: `boolean`

***

### fromMimeType?

> `optional` **fromMimeType**: `string`

***

### toMimeType?

> `optional` **toMimeType**: `string`

***

### converters?

> `optional` **converters**: [`MediaConverterTypes`](../type-aliases/MediaConverterTypes.md)[]

***

### binaryState?

> `optional` **binaryState**: `boolean`

***

### tampered?

> `optional` **tampered**: [`TamperState`](../type-aliases/TamperState.md)

***

### powerDetected?

> `optional` **powerDetected**: `boolean`

***

### audioDetected?

> `optional` **audioDetected**: `boolean`

***

### motionDetected?

> `optional` **motionDetected**: `boolean`

***

### ambientLight?

> `optional` **ambientLight**: `number`

***

### occupied?

> `optional` **occupied**: `boolean`

***

### flooded?

> `optional` **flooded**: `boolean`

***

### ultraviolet?

> `optional` **ultraviolet**: `number`

***

### luminance?

> `optional` **luminance**: `number`

***

### position?

> `optional` **position**: [`Position`](Position.md)

***

### securitySystemState?

> `optional` **securitySystemState**: [`SecuritySystemState`](SecuritySystemState.md)

***

### pm10Density?

> `optional` **pm10Density**: `number`

***

### pm25Density?

> `optional` **pm25Density**: `number`

***

### vocDensity?

> `optional` **vocDensity**: `number`

***

### noxDensity?

> `optional` **noxDensity**: `number`

***

### co2ppm?

> `optional` **co2ppm**: `number`

***

### airQuality?

> `optional` **airQuality**: [`AirQuality`](../enumerations/AirQuality.md)

***

### airPurifierState?

> `optional` **airPurifierState**: [`AirPurifierState`](AirPurifierState.md)

***

### filterChangeIndication?

> `optional` **filterChangeIndication**: `boolean`

***

### filterLifeLevel?

> `optional` **filterLifeLevel**: `number`

***

### humiditySetting?

> `optional` **humiditySetting**: [`HumiditySettingStatus`](HumiditySettingStatus.md)

***

### fan?

> `optional` **fan**: [`FanStatus`](FanStatus.md)

***

### applicationInfo?

> `optional` **applicationInfo**: [`LauncherApplicationInfo`](LauncherApplicationInfo.md)

***

### systemDevice?

> `optional` **systemDevice**: [`ScryptedSystemDeviceInfo`](ScryptedSystemDeviceInfo.md)
