[Scrypted Documentation](../globals.md) / MixinDeviceBase

# Class: MixinDeviceBase\<T\>

## Extends

- [`DeviceBase`](DeviceBase.md)

## Type Parameters

• **T**

## Implements

- [`DeviceState`](../interfaces/DeviceState.md)

## Constructors

### new MixinDeviceBase()

> **new MixinDeviceBase**\<`T`\>(`options`): [`MixinDeviceBase`](MixinDeviceBase.md)\<`T`\>

#### Parameters

• **options**: [`MixinDeviceOptions`](../interfaces/MixinDeviceOptions.md)\<`T`\>

#### Returns

[`MixinDeviceBase`](MixinDeviceBase.md)\<`T`\>

#### Overrides

[`DeviceBase`](DeviceBase.md).[`constructor`](DeviceBase.md#constructors)

## Properties

### mixinProviderNativeId

> **mixinProviderNativeId**: [`ScryptedNativeId`](../type-aliases/ScryptedNativeId.md)

***

### mixinDevice

> **mixinDevice**: `T`

***

### mixinDeviceInterfaces

> **mixinDeviceInterfaces**: [`ScryptedInterface`](../enumerations/ScryptedInterface.md)[]

***

### id

> **id**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`id`](../interfaces/DeviceState.md#id)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`id`](DeviceBase.md#id)

***

### info?

> `optional` **info**: [`DeviceInformation`](../interfaces/DeviceInformation.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`info`](../interfaces/DeviceState.md#info)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`info`](DeviceBase.md#info)

***

### interfaces

> **interfaces**: `string`[]

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`interfaces`](../interfaces/DeviceState.md#interfaces)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`interfaces`](DeviceBase.md#interfaces)

***

### mixins

> **mixins**: `string`[]

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`mixins`](../interfaces/DeviceState.md#mixins)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`mixins`](DeviceBase.md#mixins)

***

### name?

> `optional` **name**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`name`](../interfaces/DeviceState.md#name)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`name`](DeviceBase.md#name)

***

### nativeId?

> `optional` **nativeId**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`nativeId`](../interfaces/DeviceState.md#nativeid)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`nativeId`](DeviceBase.md#nativeid)

***

### pluginId

> **pluginId**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`pluginId`](../interfaces/DeviceState.md#pluginid)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`pluginId`](DeviceBase.md#pluginid)

***

### providedInterfaces

> **providedInterfaces**: `string`[]

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providedInterfaces`](../interfaces/DeviceState.md#providedinterfaces)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providedInterfaces`](DeviceBase.md#providedinterfaces)

***

### providedName?

> `optional` **providedName**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providedName`](../interfaces/DeviceState.md#providedname)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providedName`](DeviceBase.md#providedname)

***

### providedRoom?

> `optional` **providedRoom**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providedRoom`](../interfaces/DeviceState.md#providedroom)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providedRoom`](DeviceBase.md#providedroom)

***

### providedType?

> `optional` **providedType**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providedType`](../interfaces/DeviceState.md#providedtype)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providedType`](DeviceBase.md#providedtype)

***

### providerId?

> `optional` **providerId**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`providerId`](../interfaces/DeviceState.md#providerid)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`providerId`](DeviceBase.md#providerid)

***

### room?

> `optional` **room**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`room`](../interfaces/DeviceState.md#room)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`room`](DeviceBase.md#room)

***

### type?

> `optional` **type**: [`ScryptedDeviceType`](../enumerations/ScryptedDeviceType.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`type`](../interfaces/DeviceState.md#type)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`type`](DeviceBase.md#type)

***

### scryptedRuntimeArguments?

> `optional` **scryptedRuntimeArguments**: [`ScryptedRuntimeArguments`](../interfaces/ScryptedRuntimeArguments.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`scryptedRuntimeArguments`](../interfaces/DeviceState.md#scryptedruntimearguments)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`scryptedRuntimeArguments`](DeviceBase.md#scryptedruntimearguments)

***

### on?

> `optional` **on**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`on`](../interfaces/DeviceState.md#on)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`on`](DeviceBase.md#on)

***

### brightness?

> `optional` **brightness**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`brightness`](../interfaces/DeviceState.md#brightness)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`brightness`](DeviceBase.md#brightness)

***

### colorTemperature?

> `optional` **colorTemperature**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`colorTemperature`](../interfaces/DeviceState.md#colortemperature)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`colorTemperature`](DeviceBase.md#colortemperature)

***

### rgb?

> `optional` **rgb**: [`ColorRgb`](../interfaces/ColorRgb.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`rgb`](../interfaces/DeviceState.md#rgb)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`rgb`](DeviceBase.md#rgb)

***

### hsv?

> `optional` **hsv**: [`ColorHsv`](../interfaces/ColorHsv.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`hsv`](../interfaces/DeviceState.md#hsv)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`hsv`](DeviceBase.md#hsv)

***

### running?

> `optional` **running**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`running`](../interfaces/DeviceState.md#running)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`running`](DeviceBase.md#running)

***

### paused?

> `optional` **paused**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`paused`](../interfaces/DeviceState.md#paused)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`paused`](DeviceBase.md#paused)

***

### docked?

> `optional` **docked**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`docked`](../interfaces/DeviceState.md#docked)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`docked`](DeviceBase.md#docked)

***

### temperatureSetting?

> `optional` **temperatureSetting**: [`TemperatureSettingStatus`](../interfaces/TemperatureSettingStatus.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`temperatureSetting`](../interfaces/DeviceState.md#temperaturesetting)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`temperatureSetting`](DeviceBase.md#temperaturesetting)

***

### temperature?

> `optional` **temperature**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`temperature`](../interfaces/DeviceState.md#temperature)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`temperature`](DeviceBase.md#temperature)

***

### temperatureUnit?

> `optional` **temperatureUnit**: [`TemperatureUnit`](../enumerations/TemperatureUnit.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`temperatureUnit`](../interfaces/DeviceState.md#temperatureunit)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`temperatureUnit`](DeviceBase.md#temperatureunit)

***

### humidity?

> `optional` **humidity**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`humidity`](../interfaces/DeviceState.md#humidity)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`humidity`](DeviceBase.md#humidity)

***

### audioVolumes?

> `optional` **audioVolumes**: [`AudioVolumes`](../interfaces/AudioVolumes.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`audioVolumes`](../interfaces/DeviceState.md#audiovolumes)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`audioVolumes`](DeviceBase.md#audiovolumes)

***

### recordingActive?

> `optional` **recordingActive**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`recordingActive`](../interfaces/DeviceState.md#recordingactive)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`recordingActive`](DeviceBase.md#recordingactive)

***

### ptzCapabilities?

> `optional` **ptzCapabilities**: [`PanTiltZoomCapabilities`](../interfaces/PanTiltZoomCapabilities.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`ptzCapabilities`](../interfaces/DeviceState.md#ptzcapabilities)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`ptzCapabilities`](DeviceBase.md#ptzcapabilities)

***

### lockState?

> `optional` **lockState**: [`LockState`](../enumerations/LockState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`lockState`](../interfaces/DeviceState.md#lockstate)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`lockState`](DeviceBase.md#lockstate)

***

### entryOpen?

> `optional` **entryOpen**: `boolean` \| `"jammed"`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`entryOpen`](../interfaces/DeviceState.md#entryopen)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`entryOpen`](DeviceBase.md#entryopen)

***

### batteryLevel?

> `optional` **batteryLevel**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`batteryLevel`](../interfaces/DeviceState.md#batterylevel)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`batteryLevel`](DeviceBase.md#batterylevel)

***

### chargeState?

> `optional` **chargeState**: [`ChargeState`](../enumerations/ChargeState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`chargeState`](../interfaces/DeviceState.md#chargestate)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`chargeState`](DeviceBase.md#chargestate)

***

### online?

> `optional` **online**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`online`](../interfaces/DeviceState.md#online)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`online`](DeviceBase.md#online)

***

### fromMimeType?

> `optional` **fromMimeType**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`fromMimeType`](../interfaces/DeviceState.md#frommimetype)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`fromMimeType`](DeviceBase.md#frommimetype)

***

### toMimeType?

> `optional` **toMimeType**: `string`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`toMimeType`](../interfaces/DeviceState.md#tomimetype)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`toMimeType`](DeviceBase.md#tomimetype)

***

### converters?

> `optional` **converters**: [`MediaConverterTypes`](../type-aliases/MediaConverterTypes.md)[]

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`converters`](../interfaces/DeviceState.md#converters)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`converters`](DeviceBase.md#converters)

***

### binaryState?

> `optional` **binaryState**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`binaryState`](../interfaces/DeviceState.md#binarystate)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`binaryState`](DeviceBase.md#binarystate)

***

### tampered?

> `optional` **tampered**: [`TamperState`](../type-aliases/TamperState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`tampered`](../interfaces/DeviceState.md#tampered)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`tampered`](DeviceBase.md#tampered)

***

### powerDetected?

> `optional` **powerDetected**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`powerDetected`](../interfaces/DeviceState.md#powerdetected)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`powerDetected`](DeviceBase.md#powerdetected)

***

### audioDetected?

> `optional` **audioDetected**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`audioDetected`](../interfaces/DeviceState.md#audiodetected)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`audioDetected`](DeviceBase.md#audiodetected)

***

### motionDetected?

> `optional` **motionDetected**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`motionDetected`](../interfaces/DeviceState.md#motiondetected)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`motionDetected`](DeviceBase.md#motiondetected)

***

### ambientLight?

> `optional` **ambientLight**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`ambientLight`](../interfaces/DeviceState.md#ambientlight)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`ambientLight`](DeviceBase.md#ambientlight)

***

### occupied?

> `optional` **occupied**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`occupied`](../interfaces/DeviceState.md#occupied)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`occupied`](DeviceBase.md#occupied)

***

### flooded?

> `optional` **flooded**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`flooded`](../interfaces/DeviceState.md#flooded)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`flooded`](DeviceBase.md#flooded)

***

### ultraviolet?

> `optional` **ultraviolet**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`ultraviolet`](../interfaces/DeviceState.md#ultraviolet)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`ultraviolet`](DeviceBase.md#ultraviolet)

***

### luminance?

> `optional` **luminance**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`luminance`](../interfaces/DeviceState.md#luminance)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`luminance`](DeviceBase.md#luminance)

***

### position?

> `optional` **position**: [`Position`](../interfaces/Position.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`position`](../interfaces/DeviceState.md#position)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`position`](DeviceBase.md#position)

***

### securitySystemState?

> `optional` **securitySystemState**: [`SecuritySystemState`](../interfaces/SecuritySystemState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`securitySystemState`](../interfaces/DeviceState.md#securitysystemstate)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`securitySystemState`](DeviceBase.md#securitysystemstate)

***

### pm10Density?

> `optional` **pm10Density**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`pm10Density`](../interfaces/DeviceState.md#pm10density)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`pm10Density`](DeviceBase.md#pm10density)

***

### pm25Density?

> `optional` **pm25Density**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`pm25Density`](../interfaces/DeviceState.md#pm25density)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`pm25Density`](DeviceBase.md#pm25density)

***

### vocDensity?

> `optional` **vocDensity**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`vocDensity`](../interfaces/DeviceState.md#vocdensity)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`vocDensity`](DeviceBase.md#vocdensity)

***

### noxDensity?

> `optional` **noxDensity**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`noxDensity`](../interfaces/DeviceState.md#noxdensity)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`noxDensity`](DeviceBase.md#noxdensity)

***

### co2ppm?

> `optional` **co2ppm**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`co2ppm`](../interfaces/DeviceState.md#co2ppm)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`co2ppm`](DeviceBase.md#co2ppm)

***

### airQuality?

> `optional` **airQuality**: [`AirQuality`](../enumerations/AirQuality.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`airQuality`](../interfaces/DeviceState.md#airquality)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`airQuality`](DeviceBase.md#airquality)

***

### airPurifierState?

> `optional` **airPurifierState**: [`AirPurifierState`](../interfaces/AirPurifierState.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`airPurifierState`](../interfaces/DeviceState.md#airpurifierstate)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`airPurifierState`](DeviceBase.md#airpurifierstate)

***

### filterChangeIndication?

> `optional` **filterChangeIndication**: `boolean`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`filterChangeIndication`](../interfaces/DeviceState.md#filterchangeindication)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`filterChangeIndication`](DeviceBase.md#filterchangeindication)

***

### filterLifeLevel?

> `optional` **filterLifeLevel**: `number`

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`filterLifeLevel`](../interfaces/DeviceState.md#filterlifelevel)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`filterLifeLevel`](DeviceBase.md#filterlifelevel)

***

### humiditySetting?

> `optional` **humiditySetting**: [`HumiditySettingStatus`](../interfaces/HumiditySettingStatus.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`humiditySetting`](../interfaces/DeviceState.md#humiditysetting)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`humiditySetting`](DeviceBase.md#humiditysetting)

***

### fan?

> `optional` **fan**: [`FanStatus`](../interfaces/FanStatus.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`fan`](../interfaces/DeviceState.md#fan)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`fan`](DeviceBase.md#fan)

***

### applicationInfo?

> `optional` **applicationInfo**: [`LauncherApplicationInfo`](../interfaces/LauncherApplicationInfo.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`applicationInfo`](../interfaces/DeviceState.md#applicationinfo)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`applicationInfo`](DeviceBase.md#applicationinfo)

***

### systemDevice?

> `optional` **systemDevice**: [`ScryptedSystemDeviceInfo`](../interfaces/ScryptedSystemDeviceInfo.md)

#### Implementation of

[`DeviceState`](../interfaces/DeviceState.md).[`systemDevice`](../interfaces/DeviceState.md#systemdevice)

#### Inherited from

[`DeviceBase`](DeviceBase.md).[`systemDevice`](DeviceBase.md#systemdevice)

## Accessors

### storage

> `get` **storage**(): `Storage`

#### Returns

`Storage`

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

> **getMediaObjectConsole**(`mediaObject`): `Console`

#### Parameters

• **mediaObject**: [`MediaObject`](../interfaces/MediaObject.md)

#### Returns

`Console`

***

### onDeviceEvent()

> **onDeviceEvent**(`eventInterface`, `eventData`): `Promise`\<`void`\>

Fire an event for this device.

#### Parameters

• **eventInterface**: `string`

• **eventData**: `any`

#### Returns

`Promise`\<`void`\>

***

### \_lazyLoadDeviceState()

> **\_lazyLoadDeviceState**(): `void`

#### Returns

`void`

***

### manageListener()

> **manageListener**(`listener`): `void`

#### Parameters

• **listener**: [`EventListenerRegister`](../interfaces/EventListenerRegister.md)

#### Returns

`void`

***

### release()

> **release**(): `void`

#### Returns

`void`
