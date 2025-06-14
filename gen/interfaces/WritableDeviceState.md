[Scrypted Documentation](../globals.md) / WritableDeviceState

# Interface: WritableDeviceState

## Extends

- [`DeviceState`](DeviceState.md)

## Properties

### id

> **id**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`id`](DeviceState.md#id)

***

### info?

> `optional` **info**: [`DeviceInformation`](DeviceInformation.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`info`](DeviceState.md#info)

***

### interfaces

> **interfaces**: `string`[]

#### Inherited from

[`DeviceState`](DeviceState.md).[`interfaces`](DeviceState.md#interfaces)

***

### mixins

> **mixins**: `string`[]

#### Inherited from

[`DeviceState`](DeviceState.md).[`mixins`](DeviceState.md#mixins)

***

### name?

> `optional` **name**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`name`](DeviceState.md#name)

***

### nativeId?

> `optional` **nativeId**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`nativeId`](DeviceState.md#nativeid)

***

### pluginId

> **pluginId**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`pluginId`](DeviceState.md#pluginid)

***

### providedInterfaces

> **providedInterfaces**: `string`[]

#### Inherited from

[`DeviceState`](DeviceState.md).[`providedInterfaces`](DeviceState.md#providedinterfaces)

***

### providedName?

> `optional` **providedName**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`providedName`](DeviceState.md#providedname)

***

### providedRoom?

> `optional` **providedRoom**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`providedRoom`](DeviceState.md#providedroom)

***

### providedType?

> `optional` **providedType**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`providedType`](DeviceState.md#providedtype)

***

### providerId?

> `optional` **providerId**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`providerId`](DeviceState.md#providerid)

***

### room?

> `optional` **room**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`room`](DeviceState.md#room)

***

### type?

> `optional` **type**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`type`](DeviceState.md#type)

***

### scryptedRuntimeArguments?

> `optional` **scryptedRuntimeArguments**: [`ScryptedRuntimeArguments`](ScryptedRuntimeArguments.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`scryptedRuntimeArguments`](DeviceState.md#scryptedruntimearguments)

***

### on?

> `optional` **on**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`on`](DeviceState.md#on)

***

### brightness?

> `optional` **brightness**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`brightness`](DeviceState.md#brightness)

***

### colorTemperature?

> `optional` **colorTemperature**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`colorTemperature`](DeviceState.md#colortemperature)

***

### rgb?

> `optional` **rgb**: [`ColorRgb`](ColorRgb.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`rgb`](DeviceState.md#rgb)

***

### hsv?

> `optional` **hsv**: [`ColorHsv`](ColorHsv.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`hsv`](DeviceState.md#hsv)

***

### buttons?

> `optional` **buttons**: `string`[]

#### Inherited from

[`DeviceState`](DeviceState.md).[`buttons`](DeviceState.md#buttons)

***

### sensors

> **sensors**: `Record`\<`string`, [`Sensor`](Sensor.md)\>

#### Inherited from

[`DeviceState`](DeviceState.md).[`sensors`](DeviceState.md#sensors)

***

### running?

> `optional` **running**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`running`](DeviceState.md#running)

***

### paused?

> `optional` **paused**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`paused`](DeviceState.md#paused)

***

### docked?

> `optional` **docked**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`docked`](DeviceState.md#docked)

***

### temperatureSetting?

> `optional` **temperatureSetting**: [`TemperatureSettingStatus`](TemperatureSettingStatus.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`temperatureSetting`](DeviceState.md#temperaturesetting)

***

### temperature?

> `optional` **temperature**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`temperature`](DeviceState.md#temperature)

***

### temperatureUnit?

> `optional` **temperatureUnit**: [`TemperatureUnit`](../enumerations/TemperatureUnit.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`temperatureUnit`](DeviceState.md#temperatureunit)

***

### humidity?

> `optional` **humidity**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`humidity`](DeviceState.md#humidity)

***

### audioVolumes?

> `optional` **audioVolumes**: [`AudioVolumes`](AudioVolumes.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`audioVolumes`](DeviceState.md#audiovolumes)

***

### recordingActive?

> `optional` **recordingActive**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`recordingActive`](DeviceState.md#recordingactive)

***

### ptzCapabilities?

> `optional` **ptzCapabilities**: [`PanTiltZoomCapabilities`](PanTiltZoomCapabilities.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`ptzCapabilities`](DeviceState.md#ptzcapabilities)

***

### lockState?

> `optional` **lockState**: [`LockState`](../enumerations/LockState.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`lockState`](DeviceState.md#lockstate)

***

### entryOpen?

> `optional` **entryOpen**: `boolean` \| `"jammed"`

#### Inherited from

[`DeviceState`](DeviceState.md).[`entryOpen`](DeviceState.md#entryopen)

***

### batteryLevel?

> `optional` **batteryLevel**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`batteryLevel`](DeviceState.md#batterylevel)

***

### chargeState?

> `optional` **chargeState**: [`ChargeState`](../enumerations/ChargeState.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`chargeState`](DeviceState.md#chargestate)

***

### online?

> `optional` **online**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`online`](DeviceState.md#online)

***

### fromMimeType?

> `optional` **fromMimeType**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`fromMimeType`](DeviceState.md#frommimetype)

***

### toMimeType?

> `optional` **toMimeType**: `string`

#### Inherited from

[`DeviceState`](DeviceState.md).[`toMimeType`](DeviceState.md#tomimetype)

***

### converters?

> `optional` **converters**: [`MediaConverterTypes`](../type-aliases/MediaConverterTypes.md)[]

#### Inherited from

[`DeviceState`](DeviceState.md).[`converters`](DeviceState.md#converters)

***

### binaryState?

> `optional` **binaryState**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`binaryState`](DeviceState.md#binarystate)

***

### tampered?

> `optional` **tampered**: [`TamperState`](../type-aliases/TamperState.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`tampered`](DeviceState.md#tampered)

***

### sleeping?

> `optional` **sleeping**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`sleeping`](DeviceState.md#sleeping)

***

### powerDetected?

> `optional` **powerDetected**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`powerDetected`](DeviceState.md#powerdetected)

***

### audioDetected?

> `optional` **audioDetected**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`audioDetected`](DeviceState.md#audiodetected)

***

### motionDetected?

> `optional` **motionDetected**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`motionDetected`](DeviceState.md#motiondetected)

***

### ambientLight?

> `optional` **ambientLight**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`ambientLight`](DeviceState.md#ambientlight)

***

### occupied?

> `optional` **occupied**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`occupied`](DeviceState.md#occupied)

***

### flooded?

> `optional` **flooded**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`flooded`](DeviceState.md#flooded)

***

### ultraviolet?

> `optional` **ultraviolet**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`ultraviolet`](DeviceState.md#ultraviolet)

***

### luminance?

> `optional` **luminance**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`luminance`](DeviceState.md#luminance)

***

### position?

> `optional` **position**: [`Position`](Position.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`position`](DeviceState.md#position)

***

### securitySystemState?

> `optional` **securitySystemState**: [`SecuritySystemState`](SecuritySystemState.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`securitySystemState`](DeviceState.md#securitysystemstate)

***

### pm10Density?

> `optional` **pm10Density**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`pm10Density`](DeviceState.md#pm10density)

***

### pm25Density?

> `optional` **pm25Density**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`pm25Density`](DeviceState.md#pm25density)

***

### vocDensity?

> `optional` **vocDensity**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`vocDensity`](DeviceState.md#vocdensity)

***

### noxDensity?

> `optional` **noxDensity**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`noxDensity`](DeviceState.md#noxdensity)

***

### co2ppm?

> `optional` **co2ppm**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`co2ppm`](DeviceState.md#co2ppm)

***

### airQuality?

> `optional` **airQuality**: [`AirQuality`](../enumerations/AirQuality.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`airQuality`](DeviceState.md#airquality)

***

### airPurifierState?

> `optional` **airPurifierState**: [`AirPurifierState`](AirPurifierState.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`airPurifierState`](DeviceState.md#airpurifierstate)

***

### filterChangeIndication?

> `optional` **filterChangeIndication**: `boolean`

#### Inherited from

[`DeviceState`](DeviceState.md).[`filterChangeIndication`](DeviceState.md#filterchangeindication)

***

### filterLifeLevel?

> `optional` **filterLifeLevel**: `number`

#### Inherited from

[`DeviceState`](DeviceState.md).[`filterLifeLevel`](DeviceState.md#filterlifelevel)

***

### humiditySetting?

> `optional` **humiditySetting**: [`HumiditySettingStatus`](HumiditySettingStatus.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`humiditySetting`](DeviceState.md#humiditysetting)

***

### fan?

> `optional` **fan**: [`FanStatus`](FanStatus.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`fan`](DeviceState.md#fan)

***

### applicationInfo?

> `optional` **applicationInfo**: [`LauncherApplicationInfo`](LauncherApplicationInfo.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`applicationInfo`](DeviceState.md#applicationinfo)

***

### systemDevice?

> `optional` **systemDevice**: [`ScryptedSystemDeviceInfo`](ScryptedSystemDeviceInfo.md)

#### Inherited from

[`DeviceState`](DeviceState.md).[`systemDevice`](DeviceState.md#systemdevice)

## Methods

### setState()

> **setState**(`property`, `value`): `Promise`\<`void`\>

#### Parameters

• **property**: `string`

• **value**: `any`

#### Returns

`Promise`\<`void`\>
