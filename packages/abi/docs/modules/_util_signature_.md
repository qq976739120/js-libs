

# Functions

<a id="eventsignature"></a>

## `<Const>` eventSignature

▸ **eventSignature**(eventName: *`string` \| `undefined`*, params?: *[ParamType](../classes/_spec_paramtype_paramtype_.paramtype.md)[]*): `object`

*Defined in [util/signature.ts:14](https://github.com/paritytech/js-libs/blob/e0c2d92/packages/abi/src/util/signature.ts#L14)*

Get event signature.

**Parameters:**

| Name | Type | Default value |
| ------ | ------ | ------ |
| eventName | `string` \| `undefined` | - |
| `Default value` params | [ParamType](../classes/_spec_paramtype_paramtype_.paramtype.md)[] |  [] |

**Returns:** `object`

___
<a id="methodsignature"></a>

## `<Const>` methodSignature

▸ **methodSignature**(methodName: *`string` \| `undefined`*, params?: *[ParamType](../classes/_spec_paramtype_paramtype_.paramtype.md)[]*): `object`

*Defined in [util/signature.ts:33](https://github.com/paritytech/js-libs/blob/e0c2d92/packages/abi/src/util/signature.ts#L33)*

Get method signature.

**Parameters:**

| Name | Type | Default value | Description |
| ------ | ------ | ------ | ------ |
| methodName | `string` \| `undefined` | - |  The method name. |
| `Default value` params | [ParamType](../classes/_spec_paramtype_paramtype_.paramtype.md)[] |  [] |  The list of params |

**Returns:** `object`

___
<a id="parsename"></a>

## `<Const>` parseName

▸ **parseName**(name: *`string` \| `undefined`*): `object`

*Defined in [util/signature.ts:47](https://github.com/paritytech/js-libs/blob/e0c2d92/packages/abi/src/util/signature.ts#L47)*

Parse name.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| name | `string` \| `undefined` |  Name to parse. |

**Returns:** `object`

___

