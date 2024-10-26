[Scrypted Documentation](../globals.md) / DeviceBase

# Class: DeviceBase

## Extended by

- [`ScryptedDeviceBase`](ScryptedDeviceBase.md)
- [`MixinDeviceBase`](MixinDeviceBase.md)

## Implements

- [`DeviceState`](../interfaces/DeviceState.md)

## Constructors

### new DeviceBase()

> **new DeviceBase**(): [`DeviceBase`](DeviceBase.md)

#### Returns

[`DeviceBase`](DeviceBase.md)

## Properties

### id

> **id**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`id`](../interfaces/DeviceState.md#id)

***

### info?

> `optional` **info**: [`DeviceInformation`](../interfaces/DeviceInformation.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`info`](../interfaces/DeviceState.md#info)

***

### interfaces

> **interfaces**: `string`[]

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`interfaces`](../interfaces/DeviceState.md#interfaces)

***

### mixins

> **mixins**: `string`[]

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`mixins`](../interfaces/DeviceState.md#mixins)

***

### name?

> `optional` **name**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`name`](../interfaces/DeviceState.md#name)

***

### nativeId?

> `optional` **nativeId**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`nativeId`](../interfaces/DeviceState.md#nativeid)

***

### pluginId

> **pluginId**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`pluginId`](../interfaces/DeviceState.md#pluginid)

***

### providedInterfaces

> **providedInterfaces**: `string`[]

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providedInterfaces`](../interfaces/DeviceState.md#providedinterfaces)

***

### providedName?

> `optional` **providedName**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providedName`](../interfaces/DeviceState.md#providedname)

***

### providedRoom?

> `optional` **providedRoom**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providedRoom`](../interfaces/DeviceState.md#providedroom)

***

### providedType?

> `optional` **providedType**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providedType`](../interfaces/DeviceState.md#providedtype)

***

### providerId?

> `optional` **providerId**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providerId`](../interfaces/DeviceState.md#providerid)

***

### room?

> `optional` **room**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`room`](../interfaces/DeviceState.md#room)

***

### type?

> `optional` **type**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`type`](../interfaces/DeviceState.md#type)

***

### scryptedRuntimeArguments?

> `optional` **scryptedRuntimeArguments**: [`ScryptedRuntimeArguments`](../interfaces/ScryptedRuntimeArguments.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`scryptedRuntimeArguments`](../interfaces/DeviceState.md#scryptedruntimearguments)

***

### on?

> `optional` **on**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`on`](../interfaces/DeviceState.md#on)

***

### brightness?

> `optional` **brightness**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`brightness`](../interfaces/DeviceState.md#brightness)

***

### colorTemperature?

> `optional` **colorTemperature**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`colorTemperature`](../interfaces/DeviceState.md#colortemperature)

***

### rgb?

> `optional` **rgb**: [`ColorRgb`](../interfaces/ColorRgb.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`rgb`](../interfaces/DeviceState.md#rgb)

***

### hsv?

> `optional` **hsv**: [`ColorHsv`](../interfaces/ColorHsv.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`hsv`](../interfaces/DeviceState.md#hsv)

***

### running?

> `optional` **running**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`running`](../interfaces/DeviceState.md#running)

***

### paused?

> `optional` **paused**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`paused`](../interfaces/DeviceState.md#paused)

***

### docked?

> `optional` **docked**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`docked`](../interfaces/DeviceState.md#docked)

***

### temperatureSetting?

> `optional` **temperatureSetting**: [`TemperatureSettingStatus`](../interfaces/TemperatureSettingStatus.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`temperatureSetting`](../interfaces/DeviceState.md#temperaturesetting)

***

### temperature?

> `optional` **temperature**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`temperature`](../interfaces/DeviceState.md#temperature)

***

### temperatureUnit?

> `optional` **temperatureUnit**: [`TemperatureUnit`](../enumerations/TemperatureUnit.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`temperatureUnit`](../interfaces/DeviceState.md#temperatureunit)

***

### humidity?

> `optional` **humidity**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`humidity`](../interfaces/DeviceState.md#humidity)

***

### audioVolumes?

> `optional` **audioVolumes**: [`AudioVolumes`](../interfaces/AudioVolumes.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`audioVolumes`](../interfaces/DeviceState.md#audiovolumes)

***

### recordingActive?

> `optional` **recordingActive**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`recordingActive`](../interfaces/DeviceState.md#recordingactive)

***

### ptzCapabilities?

> `optional` **ptzCapabilities**: [`PanTiltZoomCapabilities`](../interfaces/PanTiltZoomCapabilities.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`ptzCapabilities`](../interfaces/DeviceState.md#ptzcapabilities)

***

### lockState?

> `optional` **lockState**: [`LockState`](../enumerations/LockState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`lockState`](../interfaces/DeviceState.md#lockstate)

***

### entryOpen?

> `optional` **entryOpen**: `boolean` \| `"jammed"`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`entryOpen`](../interfaces/DeviceState.md#entryopen)

***

### batteryLevel?

> `optional` **batteryLevel**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`batteryLevel`](../interfaces/DeviceState.md#batterylevel)

***

### chargeState?

> `optional` **chargeState**: [`ChargeState`](../enumerations/ChargeState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`chargeState`](../interfaces/DeviceState.md#chargestate)

***

### online?

> `optional` **online**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`online`](../interfaces/DeviceState.md#online)

***

### fromMimeType?

> `optional` **fromMimeType**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`fromMimeType`](../interfaces/DeviceState.md#frommimetype)

***

### toMimeType?

> `optional` **toMimeType**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`toMimeType`](../interfaces/DeviceState.md#tomimetype)

***

### converters?

> `optional` **converters**: [`MediaConverterTypes`](../type-aliases/MediaConverterTypes.md)[]

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`converters`](../interfaces/DeviceState.md#converters)

***

### binaryState?

> `optional` **binaryState**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`binaryState`](../interfaces/DeviceState.md#binarystate)

***

### tampered?

> `optional` **tampered**: [`TamperState`](../type-aliases/TamperState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`tampered`](../interfaces/DeviceState.md#tampered)

***

### powerDetected?

> `optional` **powerDetected**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`powerDetected`](../interfaces/DeviceState.md#powerdetected)

***

### audioDetected?

> `optional` **audioDetected**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`audioDetected`](../interfaces/DeviceState.md#audiodetected)

***

### motionDetected?

> `optional` **motionDetected**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`motionDetected`](../interfaces/DeviceState.md#motiondetected)

***

### ambientLight?

> `optional` **ambientLight**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`ambientLight`](../interfaces/DeviceState.md#ambientlight)

***

### occupied?

> `optional` **occupied**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`occupied`](../interfaces/DeviceState.md#occupied)

***

### flooded?

> `optional` **flooded**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`flooded`](../interfaces/DeviceState.md#flooded)

***

### ultraviolet?

> `optional` **ultraviolet**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`ultraviolet`](../interfaces/DeviceState.md#ultraviolet)

***

### luminance?

> `optional` **luminance**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`luminance`](../interfaces/DeviceState.md#luminance)

***

### position?

> `optional` **position**: [`Position`](../interfaces/Position.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`position`](../interfaces/DeviceState.md#position)

***

### securitySystemState?

> `optional` **securitySystemState**: [`SecuritySystemState`](../interfaces/SecuritySystemState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`securitySystemState`](../interfaces/DeviceState.md#securitysystemstate)

***

### pm10Density?

> `optional` **pm10Density**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`pm10Density`](../interfaces/DeviceState.md#pm10density)

***

### pm25Density?

> `optional` **pm25Density**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`pm25Density`](../interfaces/DeviceState.md#pm25density)

***

### vocDensity?

> `optional` **vocDensity**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`vocDensity`](../interfaces/DeviceState.md#vocdensity)

***

### noxDensity?

> `optional` **noxDensity**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`noxDensity`](../interfaces/DeviceState.md#noxdensity)

***

### co2ppm?

> `optional` **co2ppm**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`co2ppm`](../interfaces/DeviceState.md#co2ppm)

***

### airQuality?

> `optional` **airQuality**: [`AirQuality`](../enumerations/AirQuality.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`airQuality`](../interfaces/DeviceState.md#airquality)

***

### airPurifierState?

> `optional` **airPurifierState**: [`AirPurifierState`](../interfaces/AirPurifierState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`airPurifierState`](../interfaces/DeviceState.md#airpurifierstate)

***

### filterChangeIndication?

> `optional` **filterChangeIndication**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`filterChangeIndication`](../interfaces/DeviceState.md#filterchangeindication)

***

### filterLifeLevel?

> `optional` **filterLifeLevel**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`filterLifeLevel`](../interfaces/DeviceState.md#filterlifelevel)

***

### humiditySetting?

> `optional` **humiditySetting**: [`HumiditySettingStatus`](../interfaces/HumiditySettingStatus.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`humiditySetting`](../interfaces/DeviceState.md#humiditysetting)

***

### fan?

> `optional` **fan**: [`FanStatus`](../interfaces/FanStatus.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`fan`](../interfaces/DeviceState.md#fan)

***

### applicationInfo?

> `optional` **applicationInfo**: [`LauncherApplicationInfo`](../interfaces/LauncherApplicationInfo.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`applicationInfo`](../interfaces/DeviceState.md#applicationinfo)

***

### systemDevice?

> `optional` **systemDevice**: [`ScryptedSystemDeviceInfo`](../interfaces/ScryptedSystemDeviceInfo.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`systemDevice`](../interfaces/DeviceState.md#systemdevice)
