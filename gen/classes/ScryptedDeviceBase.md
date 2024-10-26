[Scrypted Documentation](../globals.md) / ScryptedDeviceBase

# Class: ScryptedDeviceBase

## Extends

- [`DeviceBase`](DeviceBase.md)

## Constructors

### new ScryptedDeviceBase()

> **new ScryptedDeviceBase**(`nativeId`?): [`ScryptedDeviceBase`](ScryptedDeviceBase.md)

#### Parameters

• **nativeId?**: `string`

#### Returns

[`ScryptedDeviceBase`](ScryptedDeviceBase.md)

#### Overrides

[`DeviceBase`](DeviceBase.md).[`constructor`](DeviceBase.md#constructors)

## Properties

### nativeId?

> `readonly` `optional` **nativeId**: `string`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`nativeId`](DeviceBase.md#nativeid)

***

### id

> **id**: `string`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`id`](DeviceBase.md#id)

***

### info?

> `optional` **info**: [`DeviceInformation`](../interfaces/DeviceInformation.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`info`](DeviceBase.md#info)

***

### interfaces

> **interfaces**: `string`[]

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`interfaces`](DeviceBase.md#interfaces)

***

### mixins

> **mixins**: `string`[]

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`mixins`](DeviceBase.md#mixins)

***

### name?

> `optional` **name**: `string`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`name`](DeviceBase.md#name)

***

### pluginId

> **pluginId**: `string`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`pluginId`](DeviceBase.md#pluginid)

***

### providedInterfaces

> **providedInterfaces**: `string`[]

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providedInterfaces`](DeviceBase.md#providedinterfaces)

***

### providedName?

> `optional` **providedName**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providedName`](DeviceBase.md#providedname)

***

### providedRoom?

> `optional` **providedRoom**: `string`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providedRoom`](DeviceBase.md#providedroom)

***

### providedType?

> `optional` **providedType**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providedType`](DeviceBase.md#providedtype)

***

### providerId?

> `optional` **providerId**: `string`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providerId`](DeviceBase.md#providerid)

***

### room?

> `optional` **room**: `string`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`room`](DeviceBase.md#room)

***

### type?

> `optional` **type**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`type`](DeviceBase.md#type)

***

### scryptedRuntimeArguments?

> `optional` **scryptedRuntimeArguments**: [`ScryptedRuntimeArguments`](../interfaces/ScryptedRuntimeArguments.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`scryptedRuntimeArguments`](DeviceBase.md#scryptedruntimearguments)

***

### on?

> `optional` **on**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`on`](DeviceBase.md#on)

***

### brightness?

> `optional` **brightness**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`brightness`](DeviceBase.md#brightness)

***

### colorTemperature?

> `optional` **colorTemperature**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`colorTemperature`](DeviceBase.md#colortemperature)

***

### rgb?

> `optional` **rgb**: [`ColorRgb`](../interfaces/ColorRgb.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`rgb`](DeviceBase.md#rgb)

***

### hsv?

> `optional` **hsv**: [`ColorHsv`](../interfaces/ColorHsv.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`hsv`](DeviceBase.md#hsv)

***

### running?

> `optional` **running**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`running`](DeviceBase.md#running)

***

### paused?

> `optional` **paused**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`paused`](DeviceBase.md#paused)

***

### docked?

> `optional` **docked**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`docked`](DeviceBase.md#docked)

***

### temperatureSetting?

> `optional` **temperatureSetting**: [`TemperatureSettingStatus`](../interfaces/TemperatureSettingStatus.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`temperatureSetting`](DeviceBase.md#temperaturesetting)

***

### temperature?

> `optional` **temperature**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`temperature`](DeviceBase.md#temperature)

***

### temperatureUnit?

> `optional` **temperatureUnit**: [`TemperatureUnit`](../enumerations/TemperatureUnit.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`temperatureUnit`](DeviceBase.md#temperatureunit)

***

### humidity?

> `optional` **humidity**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`humidity`](DeviceBase.md#humidity)

***

### audioVolumes?

> `optional` **audioVolumes**: [`AudioVolumes`](../interfaces/AudioVolumes.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`audioVolumes`](DeviceBase.md#audiovolumes)

***

### recordingActive?

> `optional` **recordingActive**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`recordingActive`](DeviceBase.md#recordingactive)

***

### ptzCapabilities?

> `optional` **ptzCapabilities**: [`PanTiltZoomCapabilities`](../interfaces/PanTiltZoomCapabilities.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`ptzCapabilities`](DeviceBase.md#ptzcapabilities)

***

### lockState?

> `optional` **lockState**: [`LockState`](../enumerations/LockState.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`lockState`](DeviceBase.md#lockstate)

***

### entryOpen?

> `optional` **entryOpen**: `boolean` \| `"jammed"`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`entryOpen`](DeviceBase.md#entryopen)

***

### batteryLevel?

> `optional` **batteryLevel**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`batteryLevel`](DeviceBase.md#batterylevel)

***

### chargeState?

> `optional` **chargeState**: [`ChargeState`](../enumerations/ChargeState.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`chargeState`](DeviceBase.md#chargestate)

***

### online?

> `optional` **online**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`online`](DeviceBase.md#online)

***

### fromMimeType?

> `optional` **fromMimeType**: `string`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`fromMimeType`](DeviceBase.md#frommimetype)

***

### toMimeType?

> `optional` **toMimeType**: `string`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`toMimeType`](DeviceBase.md#tomimetype)

***

### converters?

> `optional` **converters**: [`MediaConverterTypes`](../type-aliases/MediaConverterTypes.md)[]

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`converters`](DeviceBase.md#converters)

***

### binaryState?

> `optional` **binaryState**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`binaryState`](DeviceBase.md#binarystate)

***

### tampered?

> `optional` **tampered**: [`TamperState`](../type-aliases/TamperState.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`tampered`](DeviceBase.md#tampered)

***

### powerDetected?

> `optional` **powerDetected**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`powerDetected`](DeviceBase.md#powerdetected)

***

### audioDetected?

> `optional` **audioDetected**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`audioDetected`](DeviceBase.md#audiodetected)

***

### motionDetected?

> `optional` **motionDetected**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`motionDetected`](DeviceBase.md#motiondetected)

***

### ambientLight?

> `optional` **ambientLight**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`ambientLight`](DeviceBase.md#ambientlight)

***

### occupied?

> `optional` **occupied**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`occupied`](DeviceBase.md#occupied)

***

### flooded?

> `optional` **flooded**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`flooded`](DeviceBase.md#flooded)

***

### ultraviolet?

> `optional` **ultraviolet**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`ultraviolet`](DeviceBase.md#ultraviolet)

***

### luminance?

> `optional` **luminance**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`luminance`](DeviceBase.md#luminance)

***

### position?

> `optional` **position**: [`Position`](../interfaces/Position.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`position`](DeviceBase.md#position)

***

### securitySystemState?

> `optional` **securitySystemState**: [`SecuritySystemState`](../interfaces/SecuritySystemState.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`securitySystemState`](DeviceBase.md#securitysystemstate)

***

### pm10Density?

> `optional` **pm10Density**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`pm10Density`](DeviceBase.md#pm10density)

***

### pm25Density?

> `optional` **pm25Density**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`pm25Density`](DeviceBase.md#pm25density)

***

### vocDensity?

> `optional` **vocDensity**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`vocDensity`](DeviceBase.md#vocdensity)

***

### noxDensity?

> `optional` **noxDensity**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`noxDensity`](DeviceBase.md#noxdensity)

***

### co2ppm?

> `optional` **co2ppm**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`co2ppm`](DeviceBase.md#co2ppm)

***

### airQuality?

> `optional` **airQuality**: [`AirQuality`](../enumerations/AirQuality.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`airQuality`](DeviceBase.md#airquality)

***

### airPurifierState?

> `optional` **airPurifierState**: [`AirPurifierState`](../interfaces/AirPurifierState.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`airPurifierState`](DeviceBase.md#airpurifierstate)

***

### filterChangeIndication?

> `optional` **filterChangeIndication**: `boolean`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`filterChangeIndication`](DeviceBase.md#filterchangeindication)

***

### filterLifeLevel?

> `optional` **filterLifeLevel**: `number`

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`filterLifeLevel`](DeviceBase.md#filterlifelevel)

***

### humiditySetting?

> `optional` **humiditySetting**: [`HumiditySettingStatus`](../interfaces/HumiditySettingStatus.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`humiditySetting`](DeviceBase.md#humiditysetting)

***

### fan?

> `optional` **fan**: [`FanStatus`](../interfaces/FanStatus.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`fan`](DeviceBase.md#fan)

***

### applicationInfo?

> `optional` **applicationInfo**: [`LauncherApplicationInfo`](../interfaces/LauncherApplicationInfo.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`applicationInfo`](DeviceBase.md#applicationinfo)

***

### systemDevice?

> `optional` **systemDevice**: [`ScryptedSystemDeviceInfo`](../interfaces/ScryptedSystemDeviceInfo.md)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`systemDevice`](DeviceBase.md#systemdevice)

## Accessors

### storage

> `get` **storage**(): `Storage`

#### Returns

`Storage`

***

### log

> `get` **log**(): [`Logger`](../interfaces/Logger.md)

#### Returns

[`Logger`](../interfaces/Logger.md)

***

### console

> `get` **console**(): `Console`

#### Returns

`Console`

## Methods

### createMediaObject()

> **createMediaObject**(`data`, `mimeType`): `Promise`\<[`MediaObject`](../interfaces/MediaObject.md) & `object`\>

#### Parameters

• **data**: `any`

• **mimeType**: `string`

#### Returns

`Promise`\<[`MediaObject`](../interfaces/MediaObject.md) & `object`\>

***

### getMediaObjectConsole()

> **getMediaObjectConsole**(`mediaObject`): `undefined` \| `Console`

#### Parameters

• **mediaObject**: [`MediaObject`](../interfaces/MediaObject.md)

#### Returns

`undefined` \| `Console`

***

### \_lazyLoadDeviceState()

> **\_lazyLoadDeviceState**(): `void`

#### Returns

`void`

***

### onDeviceEvent()

> **onDeviceEvent**(`eventInterface`, `eventData`): `Promise`\<`void`\>

Fire an event for this device.

#### Parameters

• **eventInterface**: `string`

• **eventData**: `any`

#### Returns

`Promise`\<`void`\>
