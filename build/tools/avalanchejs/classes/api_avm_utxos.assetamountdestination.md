[avalanche](../README.md) › [API-AVM-UTXOs](../modules/api_avm_utxos.md) › [AssetAmountDestination](api_avm_utxos.assetamountdestination.md)

# Class: AssetAmountDestination

## Hierarchy

* [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md)‹[TransferableOutput](api_avm_outputs.transferableoutput.md), [TransferableInput](api_avm_inputs.transferableinput.md)›

  ↳ **AssetAmountDestination**

## Index

### Constructors

* [constructor](api_avm_utxos.assetamountdestination.md#constructor)

### Properties

* [amountkey](api_avm_utxos.assetamountdestination.md#protected-amountkey)
* [amounts](api_avm_utxos.assetamountdestination.md#protected-amounts)
* [change](api_avm_utxos.assetamountdestination.md#protected-change)
* [changeAddresses](api_avm_utxos.assetamountdestination.md#protected-changeaddresses)
* [destinations](api_avm_utxos.assetamountdestination.md#protected-destinations)
* [inputs](api_avm_utxos.assetamountdestination.md#protected-inputs)
* [outputs](api_avm_utxos.assetamountdestination.md#protected-outputs)
* [senders](api_avm_utxos.assetamountdestination.md#protected-senders)

### Methods

* [addAssetAmount](api_avm_utxos.assetamountdestination.md#addassetamount)
* [addChange](api_avm_utxos.assetamountdestination.md#addchange)
* [addInput](api_avm_utxos.assetamountdestination.md#addinput)
* [addOutput](api_avm_utxos.assetamountdestination.md#addoutput)
* [assetExists](api_avm_utxos.assetamountdestination.md#assetexists)
* [canComplete](api_avm_utxos.assetamountdestination.md#cancomplete)
* [getAllOutputs](api_avm_utxos.assetamountdestination.md#getalloutputs)
* [getAmounts](api_avm_utxos.assetamountdestination.md#getamounts)
* [getAssetAmount](api_avm_utxos.assetamountdestination.md#getassetamount)
* [getChangeAddresses](api_avm_utxos.assetamountdestination.md#getchangeaddresses)
* [getChangeOutputs](api_avm_utxos.assetamountdestination.md#getchangeoutputs)
* [getDestinations](api_avm_utxos.assetamountdestination.md#getdestinations)
* [getInputs](api_avm_utxos.assetamountdestination.md#getinputs)
* [getOutputs](api_avm_utxos.assetamountdestination.md#getoutputs)
* [getSenders](api_avm_utxos.assetamountdestination.md#getsenders)

## Constructors

###  constructor

\+ **new AssetAmountDestination**(`destinations`: Array‹Buffer›, `senders`: Array‹Buffer›, `changeAddresses`: Array‹Buffer›): *[AssetAmountDestination](api_avm_utxos.assetamountdestination.md)*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[constructor](common_assetamount.standardassetamountdestination.md#constructor)*

*Defined in [src/common/assetamount.ts:186](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L186)*

**Parameters:**

Name | Type |
------ | ------ |
`destinations` | Array‹Buffer› |
`senders` | Array‹Buffer› |
`changeAddresses` | Array‹Buffer› |

**Returns:** *[AssetAmountDestination](api_avm_utxos.assetamountdestination.md)*

## Properties

### `Protected` amountkey

• **amountkey**: *object*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[amountkey](common_assetamount.standardassetamountdestination.md#protected-amountkey)*

*Defined in [src/common/assetamount.ts:113](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L113)*

___

### `Protected` amounts

• **amounts**: *Array‹[AssetAmount](common_assetamount.assetamount.md)›* = []

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[amounts](common_assetamount.standardassetamountdestination.md#protected-amounts)*

*Defined in [src/common/assetamount.ts:109](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L109)*

___

### `Protected` change

• **change**: *Array‹[TransferableOutput](api_avm_outputs.transferableoutput.md)›* = []

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[change](common_assetamount.standardassetamountdestination.md#protected-change)*

*Defined in [src/common/assetamount.ts:116](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L116)*

___

### `Protected` changeAddresses

• **changeAddresses**: *Array‹Buffer›* = []

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[changeAddresses](common_assetamount.standardassetamountdestination.md#protected-changeaddresses)*

*Defined in [src/common/assetamount.ts:112](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L112)*

___

### `Protected` destinations

• **destinations**: *Array‹Buffer›* = []

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[destinations](common_assetamount.standardassetamountdestination.md#protected-destinations)*

*Defined in [src/common/assetamount.ts:110](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L110)*

___

### `Protected` inputs

• **inputs**: *Array‹[TransferableInput](api_avm_inputs.transferableinput.md)›* = []

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[inputs](common_assetamount.standardassetamountdestination.md#protected-inputs)*

*Defined in [src/common/assetamount.ts:114](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L114)*

___

### `Protected` outputs

• **outputs**: *Array‹[TransferableOutput](api_avm_outputs.transferableoutput.md)›* = []

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[outputs](common_assetamount.standardassetamountdestination.md#protected-outputs)*

*Defined in [src/common/assetamount.ts:115](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L115)*

___

### `Protected` senders

• **senders**: *Array‹Buffer›* = []

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[senders](common_assetamount.standardassetamountdestination.md#protected-senders)*

*Defined in [src/common/assetamount.ts:111](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L111)*

## Methods

###  addAssetAmount

▸ **addAssetAmount**(`assetID`: Buffer, `amount`: BN, `burn`: BN): *void*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[addAssetAmount](common_assetamount.standardassetamountdestination.md#addassetamount)*

*Defined in [src/common/assetamount.ts:120](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L120)*

**Parameters:**

Name | Type |
------ | ------ |
`assetID` | Buffer |
`amount` | BN |
`burn` | BN |

**Returns:** *void*

___

###  addChange

▸ **addChange**(`output`: [TransferableOutput](api_avm_outputs.transferableoutput.md)): *void*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[addChange](common_assetamount.standardassetamountdestination.md#addchange)*

*Defined in [src/common/assetamount.ts:134](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L134)*

**Parameters:**

Name | Type |
------ | ------ |
`output` | [TransferableOutput](api_avm_outputs.transferableoutput.md) |

**Returns:** *void*

___

###  addInput

▸ **addInput**(`input`: [TransferableInput](api_avm_inputs.transferableinput.md)): *void*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[addInput](common_assetamount.standardassetamountdestination.md#addinput)*

*Defined in [src/common/assetamount.ts:126](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L126)*

**Parameters:**

Name | Type |
------ | ------ |
`input` | [TransferableInput](api_avm_inputs.transferableinput.md) |

**Returns:** *void*

___

###  addOutput

▸ **addOutput**(`output`: [TransferableOutput](api_avm_outputs.transferableoutput.md)): *void*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[addOutput](common_assetamount.standardassetamountdestination.md#addoutput)*

*Defined in [src/common/assetamount.ts:130](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L130)*

**Parameters:**

Name | Type |
------ | ------ |
`output` | [TransferableOutput](api_avm_outputs.transferableoutput.md) |

**Returns:** *void*

___

###  assetExists

▸ **assetExists**(`assetHexStr`: string): *boolean*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[assetExists](common_assetamount.standardassetamountdestination.md#assetexists)*

*Defined in [src/common/assetamount.ts:158](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L158)*

**Parameters:**

Name | Type |
------ | ------ |
`assetHexStr` | string |

**Returns:** *boolean*

___

###  canComplete

▸ **canComplete**(): *boolean*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[canComplete](common_assetamount.standardassetamountdestination.md#cancomplete)*

*Defined in [src/common/assetamount.ts:178](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L178)*

**Returns:** *boolean*

___

###  getAllOutputs

▸ **getAllOutputs**(): *Array‹[TransferableOutput](api_avm_outputs.transferableoutput.md)›*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getAllOutputs](common_assetamount.standardassetamountdestination.md#getalloutputs)*

*Defined in [src/common/assetamount.ts:174](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L174)*

**Returns:** *Array‹[TransferableOutput](api_avm_outputs.transferableoutput.md)›*

___

###  getAmounts

▸ **getAmounts**(): *Array‹[AssetAmount](common_assetamount.assetamount.md)›*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getAmounts](common_assetamount.standardassetamountdestination.md#getamounts)*

*Defined in [src/common/assetamount.ts:138](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L138)*

**Returns:** *Array‹[AssetAmount](common_assetamount.assetamount.md)›*

___

###  getAssetAmount

▸ **getAssetAmount**(`assetHexStr`: string): *[AssetAmount](common_assetamount.assetamount.md)*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getAssetAmount](common_assetamount.standardassetamountdestination.md#getassetamount)*

*Defined in [src/common/assetamount.ts:154](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L154)*

**Parameters:**

Name | Type |
------ | ------ |
`assetHexStr` | string |

**Returns:** *[AssetAmount](common_assetamount.assetamount.md)*

___

###  getChangeAddresses

▸ **getChangeAddresses**(): *Array‹Buffer›*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getChangeAddresses](common_assetamount.standardassetamountdestination.md#getchangeaddresses)*

*Defined in [src/common/assetamount.ts:150](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L150)*

**Returns:** *Array‹Buffer›*

___

###  getChangeOutputs

▸ **getChangeOutputs**(): *Array‹[TransferableOutput](api_avm_outputs.transferableoutput.md)›*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getChangeOutputs](common_assetamount.standardassetamountdestination.md#getchangeoutputs)*

*Defined in [src/common/assetamount.ts:170](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L170)*

**Returns:** *Array‹[TransferableOutput](api_avm_outputs.transferableoutput.md)›*

___

###  getDestinations

▸ **getDestinations**(): *Array‹Buffer›*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getDestinations](common_assetamount.standardassetamountdestination.md#getdestinations)*

*Defined in [src/common/assetamount.ts:142](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L142)*

**Returns:** *Array‹Buffer›*

___

###  getInputs

▸ **getInputs**(): *Array‹[TransferableInput](api_avm_inputs.transferableinput.md)›*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getInputs](common_assetamount.standardassetamountdestination.md#getinputs)*

*Defined in [src/common/assetamount.ts:162](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L162)*

**Returns:** *Array‹[TransferableInput](api_avm_inputs.transferableinput.md)›*

___

###  getOutputs

▸ **getOutputs**(): *Array‹[TransferableOutput](api_avm_outputs.transferableoutput.md)›*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getOutputs](common_assetamount.standardassetamountdestination.md#getoutputs)*

*Defined in [src/common/assetamount.ts:166](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L166)*

**Returns:** *Array‹[TransferableOutput](api_avm_outputs.transferableoutput.md)›*

___

###  getSenders

▸ **getSenders**(): *Array‹Buffer›*

*Inherited from [StandardAssetAmountDestination](common_assetamount.standardassetamountdestination.md).[getSenders](common_assetamount.standardassetamountdestination.md#getsenders)*

*Defined in [src/common/assetamount.ts:146](https://github.com/ava-labs/avalanchejs/blob/ccc6083/src/common/assetamount.ts#L146)*

**Returns:** *Array‹Buffer›*
