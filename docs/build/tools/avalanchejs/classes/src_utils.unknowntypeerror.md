[avalanche](../README.md) › [src/utils](../modules/src_utils.md) › [UnknownTypeError](src_utils.unknowntypeerror.md)

# Class: UnknownTypeError

## Hierarchy

  ↳ [AvalancheError](src_utils.avalancheerror.md)

  ↳ **UnknownTypeError**

## Index

### Constructors

* [constructor](src_utils.unknowntypeerror.md#constructor)

### Properties

* [errorCode](src_utils.unknowntypeerror.md#errorcode)
* [message](src_utils.unknowntypeerror.md#message)
* [name](src_utils.unknowntypeerror.md#name)
* [stack](src_utils.unknowntypeerror.md#optional-stack)

### Methods

* [getCode](src_utils.unknowntypeerror.md#getcode)

## Constructors

###  constructor

\+ **new UnknownTypeError**(`m`: string): *[UnknownTypeError](src_utils.unknowntypeerror.md)*

*Overrides [AvalancheError](src_utils.avalancheerror.md).[constructor](src_utils.avalancheerror.md#constructor)*

*Defined in [src/utils/errors.ts:316](https://github.com/ava-labs/avalanchejs/blob/8c220c6/src/utils/errors.ts#L316)*

**Parameters:**

Name | Type |
------ | ------ |
`m` | string |

**Returns:** *[UnknownTypeError](src_utils.unknowntypeerror.md)*

## Properties

###  errorCode

• **errorCode**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[errorCode](src_utils.avalancheerror.md#errorcode)*

*Defined in [src/utils/errors.ts:45](https://github.com/ava-labs/avalanchejs/blob/8c220c6/src/utils/errors.ts#L45)*

___

###  message

• **message**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[message](src_utils.avalancheerror.md#message)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1023

___

###  name

• **name**: *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[name](src_utils.avalancheerror.md#name)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1022

___

### `Optional` stack

• **stack**? : *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[stack](src_utils.avalancheerror.md#optional-stack)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:1024

## Methods

###  getCode

▸ **getCode**(): *string*

*Inherited from [AvalancheError](src_utils.avalancheerror.md).[getCode](src_utils.avalancheerror.md#getcode)*

*Defined in [src/utils/errors.ts:52](https://github.com/ava-labs/avalanchejs/blob/8c220c6/src/utils/errors.ts#L52)*

**Returns:** *string*
