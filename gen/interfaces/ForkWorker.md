[Scrypted Documentation](../globals.md) / ForkWorker

# Interface: ForkWorker

## Extends

- `Disposable`

## Properties

### nativeWorker?

> `optional` **nativeWorker**: `ChildProcess` \| `Worker`

## Methods

### \[dispose\]()

> **\[dispose\]**(): `void`

#### Returns

`void`

#### Inherited from

`Disposable.[dispose]`

***

### terminate()

> **terminate**(): `void`

#### Returns

`void`

***

### on()

#### on(event, listener)

> **on**(`event`, `listener`): `void`

##### Parameters

• **event**: `"exit"`

• **listener**

##### Returns

`void`

#### on(event, listener)

> **on**(`event`, `listener`): `void`

##### Parameters

• **event**: `"error"`

• **listener**

##### Returns

`void`

***

### removeListener()

#### removeListener(event, listener)

> **removeListener**(`event`, `listener`): `void`

##### Parameters

• **event**: `"exit"`

• **listener**

##### Returns

`void`

#### removeListener(event, listener)

> **removeListener**(`event`, `listener`): `void`

##### Parameters

• **event**: `"error"`

• **listener**

##### Returns

`void`
